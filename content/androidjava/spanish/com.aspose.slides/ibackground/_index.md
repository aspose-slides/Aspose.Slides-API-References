---
title: IBackground
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa el fondo de una diapositiva.
type: docs
url: /es/com.aspose.slides/ibackground/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Representa el fondo de una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | Devuelve un tipo de relleno de fondo. |
| [setType(byte value)](#setType-byte-) | Devuelve un tipo de relleno de fondo. |
| [getFillFormat()](#getFillFormat--) | Devuelve un FillFormat para el relleno BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve un EffectFormat para el relleno BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Devuelve un ColorFormat para un relleno BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. |
| [getEffective()](#getEffective--) | Obtiene los datos de fondo efectivos con la herencia aplicada. |
### getType() {#getType--}
```
public abstract byte getType()
```

Devuelve un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Devuelve:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Devuelve un tipo de relleno de fondo. Lectura/escritura [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Devuelve un FillFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Devuelve un EffectFormat para el relleno BackgroundType.OwnBackground. Solo lectura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Devuelve:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Devuelve un ColorFormat para un relleno BackgroundType.Themed. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

**Devuelve:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Devuelve un índice del relleno BackgroundType.Themed en la colección de temas de fondo. 0 significa sin relleno. 1..999 - índice. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Obtiene los datos de fondo efectivos con la herencia aplicada.

**Devuelve:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Un [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).