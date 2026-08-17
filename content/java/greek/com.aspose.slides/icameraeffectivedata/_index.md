---
title: ICameraEffectiveData
second_title: Aspose.Slides για Java API Αναφορά
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες της κάμερας.
type: docs
url: /el/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες της κάμερας.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCameraType()](#getCameraType--) | Τύπος κάμερας. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | FOV κάμερας (0-180 μοίρες, πεδίο θέασης). |
| [getZoom()](#getZoom--) | Ζουμ κάμερας (θετική τιμή σε ποσοστό). |
| [getRotation()](#getRotation--) | Η περιστροφή ορίζεται μέσω χρήσης ενός συντεταγμένου γεωγραφικού πλάτους, ενός συντεταγμένου γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τα συντεταγμένα πλάτους και μήκους. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

Τύπος κάμερας. Μόνο για ανάγνωση [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Επιστρέφει:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

FOV κάμερας (0-180 μοίρες, πεδίο θέασης). Μόνο για ανάγνωση float.

**Επιστρέφει:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

Ζουμ κάμερας (θετική τιμή σε ποσοστό). Μόνο για ανάγνωση float.

**Επιστρέφει:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Η περιστροφή ορίζεται μέσω χρήσης ενός συντεταγμένου γεωγραφικού πλάτους, ενός συντεταγμένου γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τα συντεταγμένα πλάτους και μήκους. Το πρώτο στοιχείο στον πίνακα επιστροφής - γεωγραφικό πλάτος, το δεύτερο - γεωγραφικό μήκος, το τρίτο - επανάληψη. Επιστρέφει null εάν δεν ορίζεται περιστροφή.

**Επιστρέφει:**
float[] - Πίνακας τιμών περιστροφής ως float[].