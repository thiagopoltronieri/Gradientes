# Gradientes em CSS3 e HTML5

## Sumário

- [Gradientes em CSS3 e HTML5](#gradientes-em-css3-e-html5)
  - [Sumário](#sumário)
  - [Introdução](#introdução)
  - [HTML5](#html5)
  - [CSS3](#css3)
    - [Gradiente Linear](#gradiente-linear)
      - [Parâmetros](#parâmetros)
    - [Gradiente Radial](#gradiente-radial)
      - [Parâmetros](#parâmetros-1)
    - [Gradiente Linear Repetitivo](#gradiente-linear-repetitivo)
      - [Parâmetros](#parâmetros-2)
    - [Gradiente Radial Repetitivo](#gradiente-radial-repetitivo)
      - [Parâmetros](#parâmetros-3)

## Introdução

Esta documentação aborda os conceitos de gradientes em CSS3 e HTML5. Os gradientes permitem criar transições suaves entre duas ou mais cores, e são amplamente usados em design de UI.

## HTML5

HTML5 é a versão mais recente do HTML e oferece suporte completo para estilos CSS3, incluindo gradientes. No exemplo fornecido, usamos um simples esqueleto HTML5 para aplicar os estilos CSS.

```html
<!DOCTYPE html>
<html lang="pt-BR">
<!-- Código omitido -->
</html>
```

## CSS3

CSS3 introduziu várias novas funcionalidades, incluindo gradientes. Abaixo estão os tipos de gradientes mais comuns.

### Gradiente Linear

Um gradiente linear cria uma transição suave ao longo de uma linha reta. É definido usando a função `linear-gradient()`.

```css
.gradiente-linear {
  background-image: linear-gradient(to right, red, yellow);
}
```

#### Parâmetros

- Direção (`to right`, `to left`, `to top`, `to bottom`, ou um ângulo)
- Cores (pelo menos duas)

### Gradiente Radial

Um gradiente radial começa em um ponto central e se espalha em todas as direções. É definido usando a função `radial-gradient()`.

```css
.gradiente-radial {
  background-image: radial-gradient(circle, red, yellow);
}
```

#### Parâmetros

- Forma (`circle` ou `ellipse`)
- Cores (pelo menos duas)

### Gradiente Linear Repetitivo

Um gradiente linear repetitivo repete as cores em um padrão. É definido usando a função `repeating-linear-gradient()`.

```css
.gradiente-repetitivo-linear {
  background-image: repeating-linear-gradient(45deg, red, yellow 10%, green 20%);
}
```

#### Parâmetros

- Direção
- Cores e pontos de parada

### Gradiente Radial Repetitivo

Um gradiente radial repetitivo repete as cores em um padrão circular ou elíptico. É definido usando a função `repeating-radial-gradient()`.

```css
.gradiente-repetitivo-radial {
  background-image: repeating-radial-gradient(circle, red, yellow 10%, green 20%);
}
```

#### Parâmetros

- Forma
- Cores e pontos de parada
