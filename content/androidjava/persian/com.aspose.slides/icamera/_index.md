---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: نماد Camera.
type: docs
url: /fa/com.aspose.slides/icamera/
---```
public interface ICamera
```

نماد Camera.
## متدها

| متد | توضیح |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع دوربین Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | نوع دوربین Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV دوربین (0-180 درجه، میدان دید) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV دوربین (0-180 درجه، میدان دید) Read/write float. |
| [getZoom()](#getZoom--) | زوم دوربین (مقدار مثبت به درصد) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | زوم دوربین (مقدار مثبت به درصد) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع دوربین Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**بازگشت:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

نوع دوربین Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV دوربین (0-180 درجه، میدان دید) Read/write float.

**بازگشت:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

FOV دوربین (0-180 درجه، میدان دید) Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

زوم دوربین (مقدار مثبت به درصد) Read/write float.

**بازگشت:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

زوم دوربین (مقدار مثبت به درصد) Read/write float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اگر هر یک از مقادیر مختصات Float.NaN باشد، تمام چرخش تعریف نشده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| latitude | float | مقدار عرض به صورت float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. عنصر اول در آرایه بازگشتی - عرض، دوم - طول، سوم - چرخش. اگر چرخشی تعریف نشده باشد، مقدار null باز می‌گردد.

**بازگشت:**
float[] - آرایه‌ای از مقادیر چرخش به صورت float[].