---
title: LightRig
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει το LightRig.
type: docs
url: /el/com.aspose.slides/lightrig/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Αναπαριστά LightRig.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | Κατεύθυνση φωτός. |
| [setDirection(int value)](#setDirection-int-) | Κατεύθυνση φωτός. |
| [getLightType()](#getLightType--) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτισμού που μπορεί να εφαρμοστεί σε σχήμα. |
| [setLightType(int value)](#setLightType-int-) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτισμού που μπορεί να εφαρμοστεί σε σχήμα. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τις συντεταγμένες πλάτους και μήκους. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τις συντεταγμένες πλάτους και μήκους. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


Κατεύθυνση φωτός. Ανάγνωση/εγγραφή [LightingDirection](../../com.aspose.slides/lightingdirection).

**Επιστρέφει:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Κατεύθυνση φωτός. Ανάγνωση/εγγραφή [LightingDirection](../../com.aspose.slides/lightingdirection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


Αναπαριστά μια προεπιλεγμένη δεξιά φωτισμού που μπορεί να εφαρμοστεί σε σχήμα. Το light rig αναπαριστά μια ομάδα φωτών προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Επιστρέφει:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


Αναπαριστά μια προεπιλεγμένη δεξιά φωτισμού που μπορεί να εφαρμοστεί σε σχήμα. Το light rig αναπαριστά μια ομάδα φωτών προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τις συντεταγμένες πλάτους και μήκους. Εάν οποιαδήποτε τιμή συντεταγμένης είναι Float.NaN, η περιστροφή είναι ακαθόριστη.

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


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως τις συντεταγμένες πλάτους και μήκους. Το πρώτο στοιχείο στον πίνακα επιστροφής - γεωγραφικό πλάτος, το δεύτερο - γεωγραφικό μήκος, το τρίτο - επανάληψη. Επιστρέφει null εάν δεν έχει οριστεί περιστροφή.

**Επιστρέφει:**
float[]