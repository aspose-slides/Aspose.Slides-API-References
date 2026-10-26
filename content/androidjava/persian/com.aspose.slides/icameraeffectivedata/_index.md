---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /fa/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر دوربین است.

--------------------

این رابط به عنوان بخشی از [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) مورد استفاده قرار می‌گیرد.
## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع دوربین. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | زاویه دید دوربین (0-180 درجه، میدان دید). |
| [getZoom()](#getZoom--) | زوم دوربین (مقدار مثبت بر حسب درصد). |
| [getRotation()](#getRotation--) | چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع دوربین. فقط خواندنی [CameraPresetType](../../com.aspose.slides/camerapresettype).

**بازمی‌گرداند:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

زاویه دید دوربین (0-180 درجه، میدان دید). فقط خواندنی float.

**بازمی‌گرداند:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

زوم دوربین (مقدار مثبت بر حسب درصد). فقط خواندنی float.

**بازمی‌گرداند:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر آرایه بازگشتی - عرض، دوم - طول، سوم - دوران. اگر هیچ چرخشی تعریف نشده باشد مقدار null بازگردانده می‌شود.

**بازمی‌گرداند:**
float[] - آریه‌ای از مقادیر چرخش به صورت float[].