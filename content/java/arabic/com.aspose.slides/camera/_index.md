---
title: Camera
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل Camera.
type: docs
url: /ar/com.aspose.slides/camera/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

يمثل Camera.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | نوع Camera. |
| [setCameraType(int value)](#setCameraType-int-) | نوع Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | زاوية رؤية Camera (0-180 درجة، مجال الرؤية). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | زاوية رؤية Camera (0-180 درجة، مجال الرؤية). |
| [getZoom()](#getZoom--) | تكبير Camera (قيمة موجبة بالنسبة المئوية). |
| [setZoom(float value)](#setZoom-float-) | تكبير Camera (قيمة موجبة بالنسبة المئوية). |
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

نوع Camera. قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**القيمة المرجعة:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

نوع Camera. قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

زاوية رؤية Camera (0-180 درجة، مجال الرؤية). قراءة/كتابة float.

**القيمة المرجعة:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

زاوية رؤية Camera (0-180 درجة، مجال الرؤية). قراءة/كتابة float.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

تكبير Camera (قيمة موجبة بالنسبة المئوية). قراءة/كتابة float.

**القيمة المرجعة:**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

تكبير Camera (قيمة موجبة بالنسبة المئوية). قراءة/كتابة float.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. إذا كانت أي قيمة إحداثية هي Float.NaN، يصبح كل الدوران غير معرف.

**المعاملات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

يتم تعريف دوران من خلال استخدام إحداثي latitude وإحداثي longitude وثورة حول المحور كإحداثيات latitude و longitude. العنصر الأول في مصفوفة الإرجاع - latitude، الثاني - longitude، الثالث - revolution. إرجاع null إذا لم يتم تعريف أي دوران.

**القيمة المرجعة:**
float[]