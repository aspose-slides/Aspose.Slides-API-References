---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /ar/com.aspose.slides/icamera/
---```
public interface ICamera
```

يمثل الكاميرا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCameraType()](#getCameraType--) | نوع الكاميرا قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | نوع الكاميرا قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | مجال الرؤية للكاميرا (0-180 درجة، مجال العرض) قراءة/كتابة float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | مجال الرؤية للكاميرا (0-180 درجة، مجال العرض) قراءة/كتابة float. |
| [getZoom()](#getZoom--) | تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية) قراءة/كتابة float. |
| [setZoom(float value)](#setZoom-float-) | تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية) قراءة/كتابة float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. |
| [getRotation()](#getRotation--) | يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

نوع الكاميرا قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**القيمة المرجعة:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

نوع الكاميرا قراءة/كتابة [CameraPresetType](../../com.aspose.slides/camerapresettype).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

مجال الرؤية للكاميرا (0-180 درجة، مجال العرض) قراءة/كتابة float.

**القيمة المرجعة:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

مجال الرؤية للكاميرا (0-180 درجة، مجال العرض) قراءة/كتابة float.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية) قراءة/كتابة float.

**القيمة المرجعة:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

تكبير الكاميرا (قيمة إيجابية بالنسبة المئوية) قراءة/كتابة float.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. إذا كان أي من قيم الإحداثيات Float.NaN، يكون كل الدوران غير معرف.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| latitude | float | قيمة خط العرض float |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

يتم تعريف الدوران من خلال استخدام إحداثي خط العرض، إحداثي خط الطول، ودورة حول المحور كإحداثيات خط العرض وخط الطول. العنصر الأول في مصفوفة الإرجاع - خط العرض، الثاني - خط الطول، الثالث - الدوران. تُعيد null إذا لم يتم تعريف أي دوران.

**القيمة المرجعة:**
float[] - مصفوفة قيم الدوران كـ float[].