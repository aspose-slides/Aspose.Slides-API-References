---
title: Camera
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل Camera.
type: docs
url: /ar/com.aspose.slides/camera/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

يمثل Camera.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | نوع Camera. |
| [setCameraType(int value)](#setCameraType-int-) | نوع Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, مجال الرؤية). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, مجال الرؤية). |
| [getZoom()](#getZoom--) | Camera تكبير (قيمة موجبة بالنسبة المئوية). |
| [setZoom(float value)](#setZoom-float-) | Camera تكبير (قيمة موجبة بالنسبة المئوية). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. قراءة فقط long.

**القيمة المرجعة:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


نوع Camera. قابل للقراءة والكتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**القيمة المرجعة:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


نوع Camera. قابل للقراءة والكتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, مجال الرؤية). قابل للقراءة والكتابة float.

**القيمة المرجعة:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, مجال الرؤية). قابل للقراءة والكتابة float.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Camera تكبير (قيمة موجبة بالنسبة المئوية). قابل للقراءة والكتابة float.

**القيمة المرجعة:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Camera تكبير (قيمة موجبة بالنسبة المئوية). قابل للقراءة والكتابة float.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. إذا كان أي من قيم الإحداثيات Float.NaN، فإن جميع الدوران غير معرف.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. العنصر الأول في مصفوفة الإرجاع - latitude، الثاني - longitude، الثالث - revolution. تُرجع null إذا لم يُعرَّف أي دوران.

**القيمة المرجعة:**
float[]