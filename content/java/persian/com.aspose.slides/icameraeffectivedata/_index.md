---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /fa/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر دوربین است.

--------------------

این رابط به عنوان بخشی از [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع دوربین. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | زاویه دید دوربین (۰-۱۸۰ درجه, Field of View). |
| [getZoom()](#getZoom--) | زوم دوربین (مقدار مثبت به درصد). |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع دوربین. فقط خواندنی [CameraPresetType](../../com.aspose.slides/camerapresettype).

**باز می‌گردد:**  
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

زاویه دید دوربین (۰-۱۸۰ درجه, Field of View). فقط خواندنی float.

**باز می‌گردد:**  
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

زوم دوربین (مقدار مثبت به درصد). فقط خواندنی float.

**باز می‌گردد:**  
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و چرخش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایه بازگشتی - عرض، دومین - طول، سومین - چرخش. اگر چرخشی تعریف نشده باشد، مقدار null باز می‌گردد.

**باز می‌گردد:**  
float[] - آرایه‌ای از مقادیر چرخش به عنوان float[].