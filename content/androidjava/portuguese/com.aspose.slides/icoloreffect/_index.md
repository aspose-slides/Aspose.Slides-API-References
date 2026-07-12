---
title: IColorEffect
second_title: Referência da API Java da Aspose.Slides para Android
description: Representa um efeito de cor para um comportamento de animação.
type: docs
url: /pt/com.aspose.slides/icoloreffect/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

Representa um efeito de cor para um comportamento de animação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrom()](#getFrom--) | Este valor é usado para especificar a cor inicial do comportamento. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | Este valor é usado para especificar a cor inicial do comportamento. |
| [getTo()](#getTo--) | Descreve a cor resultante para a mudança de cor da animação. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | Descreve a cor resultante para a mudança de cor da animação. |
| [getBy()](#getBy--) | Descreve o valor de deslocamento relativo para a animação de cor. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | Descreve o valor de deslocamento relativo para a animação de cor. |
| [getColorSpace()](#getColorSpace--) | Representa o espaço de cor do comportamento. |
| [setColorSpace(int value)](#setColorSpace-int-) | Representa o espaço de cor do comportamento. |
| [getDirection()](#getDirection--) | Especifica qual direção percorrer o matiz ao redor da roda de cores. |
| [setDirection(int value)](#setDirection-int-) | Especifica qual direção percorrer o matiz ao redor da roda de cores. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```


Este valor é usado para especificar a cor inicial do comportamento. Leitura/gravação [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```


Este valor é usado para especificar a cor inicial do comportamento. Leitura/gravação [IColorFormat](../../com.aspose.slides/icolorformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```


Descreve a cor resultante para a mudança de cor da animação. Leitura/gravação [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```


Descreve a cor resultante para a mudança de cor da animação. Leitura/gravação [IColorFormat](../../com.aspose.slides/icolorformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```


Descreve o valor de deslocamento relativo para a animação de cor. Leitura/gravação [IColorOffset](../../com.aspose.slides/icoloroffset).

**Retorna:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```


Descreve o valor de deslocamento relativo para a animação de cor. Leitura/gravação [IColorOffset](../../com.aspose.slides/icoloroffset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```


Representa o espaço de cor do comportamento. Leitura/gravação [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Retorna:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```


Representa o espaço de cor do comportamento. Leitura/gravação [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Especifica qual direção percorrer o matiz ao redor da roda de cores. Leitura/gravação [ColorDirection](../../com.aspose.slides/colordirection).

**Retorna:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Especifica qual direção percorrer o matiz ao redor da roda de cores. Leitura/gravação [ColorDirection](../../com.aspose.slides/colordirection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |