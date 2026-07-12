---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto inmutable que contiene las propiedades efectivas de formato del marco de texto.
type: docs
url: /es/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Objeto inmutable que contiene las propiedades efectivas de formato del marco de texto.

--------------------

Esta interfaz se usa junto con la interfaz [ITextFrameFormat](../../com.aspose.slides/itextframeformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Méodo | Descripción |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Devuelve el estilo efectivo del texto. |
| [getMarginLeft()](#getMarginLeft--) | Devuelve el margen izquierdo (puntos) en un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Devuelve el margen derecho (puntos) en un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Devuelve el margen superior (puntos) en un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Devuelve el margen inferior (puntos) en un TextFrame. |
| [getWrapText()](#getWrapText--) | Devuelve si el texto se ajusta a los márgenes del TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Devuelve el anclaje vertical del texto en un TextFrame. |
| [getCenterText()](#getCenterText--) | Devuelve si el texto debe centrarse horizontalmente en el cuadro. |
| [getTextVerticalType()](#getTextVerticalType--) | Devuelve la orientación del texto. |
| [getAutofitType()](#getAutofitType--) | Devuelve el modo de autofit del texto. |
| [getColumnCount()](#getColumnCount--) | Especifica el número de columnas de texto en el rectángulo delimitador. |
| [getColumnSpacing()](#getColumnSpacing--) | Especifica el espacio entre columnas de texto en el área de texto (en puntos). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Devuelve el estilo efectivo del texto. Solo lectura [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Devuelve:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Devuelve el margen izquierdo (puntos) en un TextFrame. Solo lectura double.

**Devuelve:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Devuelve el margen derecho (puntos) en un TextFrame. Solo lectura double.

**Devuelve:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Devuelve el margen superior (puntos) en un TextFrame. Solo lectura double.

**Devuelve:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Devuelve el margen inferior (puntos) en un TextFrame. Solo lectura double.

**Devuelve:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Devuelve si el texto se ajusta a los márgenes del TextFrame. Solo lectura boolean.

**Devuelve:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Devuelve el anclaje vertical del texto en un TextFrame. Solo lectura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Devuelve:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Devuelve si el texto debe centrarse horizontalmente en el cuadro. Solo lectura boolean.

**Devuelve:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Devuelve la orientación del texto. Solo lectura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Devuelve:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Devuelve el modo de autofit del texto. Solo lectura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Devuelve:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Especifica el número de columnas de texto en el rectángulo delimitador. Solo lectura int.

**Devuelve:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Especifica el espacio entre columnas de texto en el área de texto (en puntos). Solo lectura float.

**Devuelve:**
float