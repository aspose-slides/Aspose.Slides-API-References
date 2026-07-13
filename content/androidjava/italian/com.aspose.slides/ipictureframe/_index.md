---
title: IPictureFrame
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un frame con un'immagine al suo interno.
type: docs
url: /it/com.aspose.slides/ipictureframe/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Rappresenta un frame contenente un'immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Restituisce i lock di PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Restituisce l'oggetto PictureFillFormat per un frame immagine. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Restituisce o imposta la scala dell'altezza (rispetto alla dimensione originale dell'immagine) del frame immagine. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Restituisce o imposta la scala dell'altezza (rispetto alla dimensione originale dell'immagine) del frame immagine. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Restituisce o imposta la scala della larghezza (rispetto alla dimensione originale dell'immagine) del frame immagine. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Restituisce o imposta la scala della larghezza (rispetto alla dimensione originale dell'immagine) del frame immagine. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Restituisce i lock di PictureFrame. Solo lettura [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Restituisce:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Restituisce l'oggetto PictureFillFormat per un frame immagine. Solo lettura [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Restituisce:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Restituisce o imposta la scala dell'altezza (rispetto alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura float.

**Restituisce:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Restituisce o imposta la scala dell'altezza (rispetto alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Restituisce o imposta la scala della larghezza (rispetto alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura float.

**Restituisce:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Restituisce o imposta la scala della larghezza (rispetto alla dimensione originale dell'immagine) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |