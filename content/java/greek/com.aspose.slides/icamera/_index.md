---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Represents Camera.
type: docs
url: /el/com.aspose.slides/icamera/
---```
public interface ICamera
```

Αναπαριστά Camera.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type Ανάγνωση/Γραφή [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera type Ανάγνωση/Γραφή [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) Ανάγνωση/Γραφή float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) Ανάγνωση/Γραφή float. |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage) Ανάγνωση/Γραφή float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage) Ανάγνωση/Γραφή float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας περιστροφής γύρω από τον άξονα ως των συντεταγμένων latitude και longitude. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας περιστροφής γύρω από τον άξονα ως των συντεταγμένων latitude και longitude. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type Ανάγνωση/Γραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Camera type Ανάγνωση/Γραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View) Ανάγνωση/Γραφή float.

**Επιστρέφει:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, field of View) Ανάγνωση/Γραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (positive value in percentage) Ανάγνωση/Γραφή float.

**Επιστρέφει:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camera zoom (positive value in percentage) Ανάγνωση/Γραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας περιστροφής γύρω από τον άξονα ως των συντεταγμένων latitude και longitude. Εάν η τιμή οποιασδήποτε συντεταγμένης είναι Float.NaN, η περιστροφή δεν ορίζεται.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| latitude | float | Latitude value float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας περιστροφής γύρω από τον άξονα ως των συντεταγμένων latitude και longitude. Το πρώτο στοιχείο στον πίνακα επιστροφής - latitude, το δεύτερο - longitude, το τρίτο - revolution. Επιστρέφει null εάν δεν έχει οριστεί περιστροφή.

**Επιστρέφει:**
float[] - Array of rotation values as float[].