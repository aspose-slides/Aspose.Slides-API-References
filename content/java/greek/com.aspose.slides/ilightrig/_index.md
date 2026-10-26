---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /el/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Αναπαριστά το LightRig.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση φωτός. |
| [setDirection(int value)](#setDirection-int-) | Κατεύθυνση φωτός. |
| [getLightType()](#getLightType--) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε ένα σχήμα. |
| [setLightType(int value)](#setLightType-int-) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε ένα σχήμα. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Κατεύθυνση φωτός. Ανάγνωση/εγγραφή [LightingDirection](../../com.aspose.slides/lightingdirection).

**Επιστρέφει:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


Κατεύθυνση φωτός. Ανάγνωση/εγγραφή [LightingDirection](../../com.aspose.slides/lightingdirection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε ένα σχήμα. Το light rig αναπαριστά μια ομάδα φωτών προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Επιστρέφει:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε ένα σχήμα. Το light rig αναπαριστά μια ομάδα φωτών προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| latitude | float | Συντεταγμένη γεωγραφικού πλάτους float |
| longitude | float | Συντεταγμένη γεωγραφικού μήκους float |
| revolution | float | Συντεταγμένη επανάληψης float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Μια περιστροφή ορίζεται μέσω της χρήσης μιας συντεταγμένης γεωγραφικού πλάτους, μιας συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωγραφικού πλάτους και γεωγραφικού μήκους. πρώτο στοιχείο στον πίνακα επιστροφής - latitude, δεύτερο - longitude, τρίτο - revolution.

**Επιστρέφει:**
float[] - Συντεταγμένες περιστροφής ως float[]