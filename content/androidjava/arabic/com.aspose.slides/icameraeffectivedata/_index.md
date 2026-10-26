---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /ar/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص الكاميرا الفعّالة.

--------------------

يُستخدم هذا الواجهة كجزء من [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع الكاميرا. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | زاوية عرض المجال للكاميرا (0-180 درجة، مجال الرؤية). |
| [getZoom()](#getZoom--) | تكبير الكاميرا (قيمة موجبة بالنسبة المئوية). |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، وثورة حول المحور كإحداثيات لخط العرض وخط الطول. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع الكاميرا. للقراءة فقط [CameraPresetType](../../com.aspose.slides/camerapresettype).

**الإرجاع:**  
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

زاوية عرض المجال للكاميرا (0-180 درجة، مجال الرؤية). للقراءة فقط float.

**الإرجاع:**  
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

تكبير الكاميرا (قيمة موجبة بالنسبة المئوية). للقراءة فقط float.

**الإرجاع:**  
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، وثورة حول المحور كإحداثيات لخط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الثورة. تُرجع null إذا لم يتم تعريف أي دوران.

**الإرجاع:**  
float[] - مصفوفة قيم الدوران كـ float[].