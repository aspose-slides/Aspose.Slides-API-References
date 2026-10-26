---
title: IBackground
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o plano de fundo de um slide.
type: docs
url: /pt/com.aspose.slides/ibackground/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Representa o plano de fundo de um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna um tipo de preenchimento de fundo. |
| [setType(byte value)](#setType-byte-) | Retorna um tipo de preenchimento de fundo. |
| [getFillFormat()](#getFillFormat--) | Retorna um FillFormat para preenchimento BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Retorna um EffectFormat para preenchimento BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Retorna um ColorFormat para um preenchimento BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. |
| [getEffective()](#getEffective--) | Obtém dados de fundo efetivos com a herança aplicada. |
### getType() {#getType--}
```
public abstract byte getType()
```


Retorna um tipo de preenchimento de fundo. Leitura/Gravação [BackgroundType](../../com.aspose.slides/backgroundtype).

**Retorna:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Retorna um tipo de preenchimento de fundo. Leitura/Gravação [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retorna um FillFormat para preenchimento BackgroundType.OwnBackground. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Retorna um EffectFormat para preenchimento BackgroundType.OwnBackground. Somente leitura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retorna:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Retorna um ColorFormat para um preenchimento BackgroundType.Themed. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. 0 significa sem preenchimento. 1..999 - índice. Leitura/Gravação int.

**Retorna:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. 0 significa sem preenchimento. 1..999 - índice. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Obtém dados de fundo efetivos com a herança aplicada.

**Retorna:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).