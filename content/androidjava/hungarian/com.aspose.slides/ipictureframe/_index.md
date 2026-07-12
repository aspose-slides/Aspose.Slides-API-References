---
title: IPictureFrame
second_title: Aspose.Slides for Android Java API hivatkozás
description: Képkeretet ábrázol, amely belül képet tartalmaz.
type: docs
url: /hu/com.aspose.slides/ipictureframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Represents a frame with a picture inside.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Visszaadja a PictureFrame's locks. |
| [getPictureFormat()](#getPictureFormat--) | Visszaadja a PictureFillFormat objektumot egy képkerethez. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel szemben) skáláját. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel szemben) skáláját. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel szemben) skáláját. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel szemben) skáláját. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```


Visszaadja a PictureFrame's locks. Csak olvasható [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Visszatérési érték:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```


Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatérési érték:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```


Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel szemben) skáláját. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Visszatérési érték:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```


Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel szemben) skáláját. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```


Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel szemben) skáláját. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Visszatérési érték:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```


Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel szemben) skáláját. Az 1.0 érték 100%-nak felel meg. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |