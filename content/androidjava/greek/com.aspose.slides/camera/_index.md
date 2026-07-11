---
title: Camera
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεύει την κάμερα.
type: docs
url: /el/com.aspose.slides/camera/
---
**Κληρονομιά:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

Αντιπροσωπεύει την κάμερα.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | Τύπος κάμερας. |
| [setCameraType(int value)](#setCameraType-int-) | Τύπος κάμερας. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Γωνία θέασης κάμερας (0-180 μοίρες, πεδίο όρασης). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Γωνία θέασης κάμερας (0-180 μοίρες, πεδίο όρασης). |
| [getZoom()](#getZoom--) | Ζουμ κάμερας (θετική τιμή σε ποσοστό). |
| [setZoom(float value)](#setZoom-float-) | Ζουμ κάμερας (θετική τιμή σε ποσοστό). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας επανάληψης γύρω από άξονα ως τις συντεταγμένες latitude και longitude. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας επανάληψης γύρω από άξονα ως τις συντεταγμένες latitude και longitude. |

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

Τύπος κάμερας. Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

Τύπος κάμερας. Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

Γωνία θέασης κάμερας (0-180 μοίρες, πεδίο όρασης). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

Γωνία θέασης κάμερας (0-180 μοίρες, πεδίο όρασης). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

Ζουμ κάμερας (θετική τιμή σε ποσοστό). Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

Ζουμ κάμερας (θετική τιμή σε ποσοστό). Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

Μια περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας επανάληψης γύρω από άξονα ως τις συντεταγμένες latitude και longitude. Εάν κάποια τιμή συντεταγμένης είναι Float.NaN, η περιστροφή είναι ακαθόριστη.

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

Μια περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης latitude, μιας συντεταγμένης longitude και μιας επανάληψης γύρω από άξονα ως τις συντεταγμένες latitude και longitude. το πρώτο στοιχείο στον πίνακα επιστροφής - latitude, το δεύτερο - longitude, το τρίτο - revolution. Επιστρέφει null εάν δεν έχει οριστεί περιστροφή.

**Επιστρέφει:**
float[]