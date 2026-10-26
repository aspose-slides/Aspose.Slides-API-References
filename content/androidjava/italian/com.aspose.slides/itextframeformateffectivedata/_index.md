---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /it/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di formattazione effettiva del text frame.

--------------------

Questa interfaccia è usata insieme all'interfaccia [ITextFrameFormat](../../com.aspose.slides/itextframeformat) per restituire i valori di formattazione effective con l'ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Restituisce lo stile del testo effective. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce il margine sinistro (punti) in un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Restituisce il margine destro (punti) in un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Restituisce il margine superiore (punti) in un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Restituisce il margine inferiore (punti) in un TextFrame. |
| [getWrapText()](#getWrapText--) | Restituisce se il testo è avvolto ai margini del TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Restituisce l'ancoraggio verticale del testo in un TextFrame. |
| [getCenterText()](#getCenterText--) | Restituisce se il testo deve essere centrato orizzontalmente nella casella. |
| [getTextVerticalType()](#getTextVerticalType--) | Restituisce l'orientamento del testo. |
| [getAutofitType()](#getAutofitType--) | Restituisce la modalità di adattamento automatico del testo. |
| [getColumnCount()](#getColumnCount--) | Specifica il numero di colonne di testo nel rettangolo di delimitazione. |
| [getColumnSpacing()](#getColumnSpacing--) | Specifica lo spazio tra le colonne di testo nell'area di testo (in punti). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Restituisce lo stile del testo effective. Solo lettura [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Restituisce:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Restituisce il margine sinistro (punti) in un TextFrame. Solo lettura double.

**Restituisce:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Restituisce il margine destro (punti) in un TextFrame. Solo lettura double.

**Restituisce:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Restituisce il margine superiore (punti) in un TextFrame. Solo lettura double.

**Restituisce:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Restituisce il margine inferiore (punti) in un TextFrame. Solo lettura double.

**Restituisce:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Restituisce se il testo è avvolto ai margini del TextFrame. Solo lettura boolean.

**Restituisce:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Restituisce l'ancoraggio verticale del testo in un TextFrame. Solo lettura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Restituisce:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Restituisce se il testo deve essere centrato orizzontalmente nella casella. Solo lettura boolean.

**Restituisce:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Restituisce l'orientamento del testo. Solo lettura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Restituisce:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Restituisce la modalità di adattamento automatico del testo. Solo lettura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Restituisce:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Specifica il numero di colonne di testo nel rettangolo di delimitazione. Solo lettura int.

**Restituisce:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Specifica lo spazio tra le colonne di testo nell'area di testo (in punti). Solo lettura float.

**Restituisce:**
float