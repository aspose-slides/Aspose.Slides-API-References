---
title: PPImage
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta un'immagine in una presentazione.
type: docs
url: /it/com.aspose.slides/ppimage/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Rappresenta un'immagine in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati di un'immagine. |
| [getImage()](#getImage--) | Restituisce una copia di un'immagine. |
| [getSvgImage()](#getSvgImage--) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Sostituisce i dati dell'immagine. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Sostituisce i dati dell'immagine. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Sostituisce i dati dell'immagine. |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un'immagine, codificato in BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Restituisce la larghezza di un'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di un'immagine. |
| [getX()](#getX--) | Restituisce l'offset X di un'immagine. |
| [getY()](#getY--) | Restituisce l'offset Y di un'immagine. |
| [hashCode()](#hashCode--) | Restituisce il codice hash di un'immagine. |
| [dispose()](#dispose--) | Rilascia l'oggetto. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Restituisce una copia dei dati di un'immagine. Solo lettura byte[] .

**Restituisce:**
byte[] - Array di byte
### getImage() {#getImage--}
```
public final IImage getImage()
```


Restituisce una copia di un'immagine. Solo lettura [IImage](../../com.aspose.slides/iimage).

**Restituisce:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che questa immagine è stata creata da SVG.

**Restituisce:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che questa immagine è stata creata da SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Sostituisce i dati dell'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImageData | byte[] | I dati della nuova immagine. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Sostituisce i dati dell'immagine. Attenzione: quando Image è metafile - verrà rasterizzata. Usa ReplaceImage(byte[]) invece

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) |  |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Sostituisce i dati dell'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Restituisce un tipo MIME di un'immagine, codificato in BinaryData (\#getBinaryData.getBinaryData). Solo lettura String.

**Restituisce:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza di un'immagine. Solo lettura int .

**Restituisce:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza di un'immagine. Solo lettura int .

**Restituisce:**
int
### getX() {#getX--}
```
public final int getX()
```


Restituisce l'offset X di un'immagine. Solo lettura int .

**Restituisce:**
int
### getY() {#getY--}
```
public final int getY()
```


Restituisce l'offset Y di un'immagine. Solo lettura int .

**Restituisce:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash di un'immagine.

**Restituisce:**
int - Hash code.
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia l'oggetto.