---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: نمایانگر دوربین.
type: docs
url: /fa/com.aspose.slides/icamera/
---```
public interface ICamera
```

نمایانگر دوربین.
## متدها

| متد | توضیح |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type خواندنی/نوشتنی [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera type خواندنی/نوشتنی [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) خواندنی/نوشتنی float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) خواندنی/نوشتنی float. |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage) خواندنی/نوشتنی float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage) خواندنی/نوشتنی float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | یک چرخش از طریق استفاده از مختصات latitude، مختصات longitude و یک دوران حول محور همانند مختصات latitude و longitude تعریف می‌شود. |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات latitude، مختصات longitude و یک دوران حول محور همانند مختصات latitude و longitude تعریف می‌شود. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type خواندنی/نوشتنی [CameraPresetType](../../com.aspose.slides/camerapresettype).

**بازگشت:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Camera type خواندنی/نوشتنی [CameraPresetType](../../com.aspose.slides/camerapresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View) خواندنی/نوشتنی float.

**بازگشت:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, field of View) خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (positive value in percentage) خواندنی/نوشتنی float.

**بازگشت:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camera zoom (positive value in percentage) خواندنی/نوشتنی float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


یک چرخش از طریق استفاده از مختصات latitude، مختصات longitude و یک دوران حول محور همانند مختصات latitude و longitude تعریف می‌شود. اگر هر یک از مقدار مختصات Float.NaN باشد، تمام چرخش تعریف نشده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| latitude | float | مقدار latitude به صورت float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


یک چرخش از طریق استفاده از مختصات latitude، مختصات longitude و یک دوران حول محور همانند مختصات latitude و longitude تعریف می‌شود. عنصر اول در آرایه بازگشتی - latitude، دوم - longitude، سوم - revolution. اگر چرخشی تعریف نشده باشد، مقدار null بازگردانده می‌شود.

**بازگشت:**
float[] - آرایه‌ای از مقادیر چرخش به صورت float[].