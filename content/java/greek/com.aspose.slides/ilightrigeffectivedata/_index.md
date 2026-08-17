---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες του light rig.
type: docs
url: /el/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει αποτελεσματικές ιδιότητες του light rig.

--------------------

Αυτή η διεπαφή χρησιμοποιείται ως μέρος του [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση φωτός. |
| [getLightType()](#getLightType--) | Αντιπροσωπεύει ένα προκαθορισμένο light right που μπορεί να εφαρμοστεί σε σχήμα. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης συντεταγμένης γεωγραφικού πλάτους, συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως συντεταγμένες πλάτους και μήκους. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


Κατεύθυνση φωτός. Μόνο για ανάγνωση [LightingDirection](../../com.aspose.slides/lightingdirection).

**Επιστρέφει:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


Αντιπροσωπεύει ένα προκαθορισμένο light right που μπορεί να εφαρμοστεί σε σχήμα. Το light rig αντιπροσωπεύει μια ομάδα φωτών προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Μόνο για ανάγνωση [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Επιστρέφει:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


Μια περιστροφή ορίζεται μέσω της χρήσης συντεταγμένης γεωγραφικού πλάτους, συντεταγμένης γεωγραφικού μήκους και μιας επανάληψης γύρω από τον άξονα ως συντεταγμένες πλάτους και μήκους. Το πρώτο στοιχείο στον πίνακα επιστροφής - γεωγραφικό πλάτος, το δεύτερο - γεωγραφικό μήκος, το τρίτο - επανάληψη.

**Επιστρέφει:**
float[] - Συντεταγμένες περιστροφής ως float[]