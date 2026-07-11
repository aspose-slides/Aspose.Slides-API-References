---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
url: /el/com.aspose.slides/icamera/
---```
public interface ICamera
```

Αντιπροσωπεύει την Κάμερα.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Τύπος κάμερας Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Τύπος κάμερας Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Κάμερα FOV (0-180 μοίρες, πεδίο θέασης) Ανάγνωση/εγγραφή float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Κάμερα FOV (0-180 μοίρες, πεδίο θέασης) Ανάγνωση/εγγραφή float. |
| [getZoom()](#getZoom--) | Ζουμ κάμερας (θετική τιμή σε ποσοστό) Ανάγνωση/εγγραφή float. |
| [setZoom(float value)](#setZoom-float-) | Ζουμ κάμερας (θετική τιμή σε ποσοστό) Ανάγνωση/εγγραφή float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μία περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης γεωγώνιου, μιας συντεταγμένης γεωδαιτικού και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγώνιου και γεωδαιτικού. |
| [getRotation()](#getRotation--) | Μία περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης γεωγώνιου, μιας συντεταγμένης γεωδαιτικού και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγώνιου και γεωδαιτικού. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Τύπος κάμερας Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

Τύπος κάμερας Ανάγνωση/εγγραφή [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

Κάμερα FOV (0-180 μοίρες, πεδίο θέασης) Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

Κάμερα FOV (0-180 μοίρες, πεδίο θέασης) Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Ζουμ κάμερας (θετική τιμή σε ποσοστό) Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

Ζουμ κάμερας (θετική τιμή σε ποσοστό) Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Μία περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης γεωγώνιου, μιας συντεταγμένης γεωδαιτικού και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγώνιου και γεωδαιτικού. Εάν οποιαδήποτε τιμή συντεταγμένης είναι Float.NaN, όλη η περιστροφή είναι ακαθόριστη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Τιμή γεωγώνιου float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Μία περιστροφή ορίζεται με τη χρήση μιας συντεταγμένης γεωγώνιου, μιας συντεταγμένης γεωδαιτικού και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγώνιου και γεωδαιτικού. το πρώτο στοιχείο στον πίνακα επιστροφής - γεωγώνιο, το δεύτερο - γεωδαιτικό, το τρίτο - επανάληψη. Επιστρέφει null εάν δεν έχει οριστεί περιστροφή.

**Επιστρέφει:**
float[] - Πίνακας τιμών περιστροφής ως float[].