---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /es/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Objeto inmutable que contiene propiedades de formato de párrafo efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [IParagraphFormat](../../com.aspose.slides/iparagraphformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBullet()](#getBullet--) | Devuelve un formato de viñeta de un párrafo. |
| [getDepth()](#getDepth--) | Devuelve la profundidad de un párrafo. |
| [getAlignment()](#getAlignment--) | Devuelve la alineación del texto en un párrafo. |
| [getSpaceWithin()](#getSpaceWithin--) | Devuelve la cantidad de espacio entre líneas base en un párrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Devuelve la cantidad de espacio antes de la primera línea en un párrafo. |
| [getSpaceAfter()](#getSpaceAfter--) | Devuelve la cantidad de espacio después de la última línea en un párrafo. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina si se usa la ruptura de línea de Asia Oriental en un párrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina si se usa la escritura de derecha a izquierda en un párrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina si se usa la ruptura de línea latina en un párrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina si se usa la puntuación colgante en un párrafo. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve el margen izquierdo en un párrafo. |
| [getMarginRight()](#getMarginRight--) | Devuelve el margen derecho en un párrafo. |
| [getIndent()](#getIndent--) | Devuelve la sangría de primera línea/sangría colgante del párrafo. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Devuelve el tamaño de tabulación predeterminado. |
| [getTabs()](#getTabs--) | Devuelve las tabulaciones de un párrafo. |
| [getFontAlignment()](#getFontAlignment--) | Devuelve la alineación de fuente en un párrafo. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Devuelve el formato de porción predeterminado de un párrafo. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Devuelve un formato de viñeta de un párrafo. Solo lectura [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Devuelve:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Devuelve la profundidad de un párrafo. Solo lectura short.

**Devuelve:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Devuelve la alineación del texto en un párrafo. Solo lectura [TextAlignment](../../com.aspose.slides/textalignment).

**Devuelve:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Devuelve la cantidad de espacio entre líneas base en un párrafo. Solo lectura float.

**Devuelve:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Devuelve la cantidad de espacio antes de la primera línea en un párrafo. Solo lectura float.

**Devuelve:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Devuelve la cantidad de espacio después de la última línea en un párrafo. Solo lectura float.

**Devuelve:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Determina si se usa la ruptura de línea de Asia Oriental en un párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determina si se usa la escritura de derecha a izquierda en un párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Determina si se usa la ruptura de línea latina en un párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Determina si se usa la puntuación colgante en un párrafo. Solo lectura boolean.

**Devuelve:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Devuelve el margen izquierdo en un párrafo. Solo lectura float.

**Devuelve:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Devuelve el margen derecho en un párrafo. Solo lectura float.

**Devuelve:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Devuelve la sangría de primera línea/sangría colgante del párrafo. La sangría colgante puede definirse con valores negativos. Solo lectura float.

**Devuelve:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Devuelve el tamaño de tabulación predeterminado. Solo lectura float.

**Devuelve:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Devuelve las tabulaciones de un párrafo. Solo lectura ITabEffectiveData[].

**Devuelve:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Devuelve la alineación de fuente en un párrafo. Solo lectura [FontAlignment](../../com.aspose.slides/fontalignment).

**Devuelve:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Devuelve el formato de porción predeterminado de un párrafo. Solo lectura [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Devuelve:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)