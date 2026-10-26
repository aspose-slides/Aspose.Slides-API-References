---
title: Camera
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει Camera.
type: docs
url: /el/com.aspose.slides/camera/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Αντιπροσωπεύει Camera.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Τύπος Camera. |
| [setCameraType(int value)](#setCameraType-int-) | Τύπος Camera. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV Camera (0-180 deg, πεδίο όρασης). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | FOV Camera (0-180 deg, πεδίο όρασης). |
| [getZoom()](#getZoom--) | Zoom Camera (θετική τιμή σε ποσοστό). |
| [setZoom(float value)](#setZoom-float-) | Zoom Camera (θετική τιμή σε ποσοστό). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

Τύπος Camera. Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Τύπος Camera. Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

FOV Camera (0-180 deg, πεδίο όρασης). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

FOV Camera (0-180 deg, πεδίο όρασης). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Zoom Camera (θετική τιμή σε ποσοστό). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Zoom Camera (θετική τιμή σε ποσοστό). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. Εάν οποιαδήποτε τιμή συντεταγμένης είναι Float.NaN, η περιστροφή είναι ακαθόριστη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. Το πρώτο στοιχείο στον πίνακα επιστροφής είναι το πλάτος, το δεύτερο το μήκος, το τρίτο η επανάληψη. Επιστρέφει null εάν δεν υπάρχει ορισμένη περιστροφή.

**Επιστρέφει:**
float[]