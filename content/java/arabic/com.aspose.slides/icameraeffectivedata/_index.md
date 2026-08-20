---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص الكاميرا الفعالة.
type: docs
url: /ar/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص الكاميرا الفعالة.

--------------------

يُستخدم هذا الواجهة كجزء من [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع الكاميرا. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | مجال رؤية الكاميرا (0-180 درجة، مجال الرؤية). |
| [getZoom()](#getZoom--) | تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية). |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، وثورة حول المحور كإحداثي خط العرض وخط الطول. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع الكاميرا. قراءة فقط [CameraPresetType](../../com.aspose.slides/camerapresettype).

**الإرجاع:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

مجال رؤية الكاميرا (0-180 درجة، مجال الرؤية). قراءة فقط float.

**الإرجاع:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية). قراءة فقط float.

**الإرجاع:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، وثورة حول المحور كإحداثي خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الثورة. إرجاع null إذا لم يتم تعريف دوران.

**الإرجاع:**
float[] - مصفوفة قيم الدوران كـ float[].