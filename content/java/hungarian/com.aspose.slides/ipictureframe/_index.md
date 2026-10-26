---
title: IPictureFrame
second_title: Aspose.Slides Java API Referencia
description: Képkeretet képeltet meg.
type: docs
url: /hu/com.aspose.slides/ipictureframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Képkeretet képeltet meg.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Visszaadja a PictureFrame zárolásait. |
| [getPictureFormat()](#getPictureFormat--) | Visszaadja a képkerethez tartozó PictureFillFormat objektumot. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) léptékét. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) léptékét. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) léptékét. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) léptékét. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Visszaadja a PictureFrame zárolásait. Csak olvasható [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Visszatér:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Visszaadja a képkerethez tartozó PictureFillFormat objektumot. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Visszaadja vagy beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) léptékét. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Visszatér:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Visszaadja vagy beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) léptékét. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Visszaadja vagy beállítja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) léptékét. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Visszatér:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Visszaadja vagy beállítja a képkeret szélességének (az eredti kép méretéhez viszonyítva) léptékét. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |