---
title: ICamera
second_title: Aspose.Slides لـ Java دليل API
description: يمثل الكاميرا.
type: docs
url: /ar/com.aspose.slides/icamera/
---```
public interface ICamera
```

يمثل الكاميرا.
## الطرق

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع الكاميرا Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | نوع الكاميرا Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | زاوية عرض الكاميرا (0-180 deg, field of View) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | زاوية عرض الكاميرا (0-180 deg, field of View) Read/write float. |
| [getZoom()](#getZoom--) | تكبير الكاميرا (قيمة موجبة بالنسبة المئوية) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | تكبير الكاميرا (قيمة موجبة بالنسبة المئوية) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف دوران من خلال استخدام إحداثي خط العرض وإحداثي خط الطول وثورة حول المحور كإحداثيات خط العرض وخط الطول. |
| [getRotation()](#getRotation--) | يتم تعريف دوران من خلال استخدام إحداثي خط العرض وإحداثي خط الطول وثورة حول المحور كإحداثيات خط العرض وخط الطول. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع الكاميرا Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**القيمة المرجعة:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

نوع الكاميرا Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

زاوية عرض الكاميرا (0-180 deg, field of View) Read/write float.

**القيمة المرجعة:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

زاوية عرض الكاميرا (0-180 deg, field of View) Read/write float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

تكبير الكاميرا (قيمة موجبة بالنسبة المئوية) Read/write float.

**القيمة المرجعة:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

تكبير الكاميرا (قيمة موجبة بالنسبة المئوية) Read/write float.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف دوران من خلال استخدام إحداثي خط العرض وإحداثي خط الطول وثورة حول المحور كإحداثيات خط العرض وخط الطول. إذا كانت أي قيمة من الإحداثيات هي Float.NaN، فإن جميع الدورانات غير معرفة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| latitude | float | قيمة خط العرض float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي خط العرض وإحداثي خط الطول وثورة حول المحور كإحداثيات خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع – خط العرض، الثاني – خط الطول، الثالث – الثورة. تُرجع null إذا لم يتم تعريف أي دوران.

**القيمة المرجعة:**
float[] - مصفوفة من قيم الدوران كـ float[].