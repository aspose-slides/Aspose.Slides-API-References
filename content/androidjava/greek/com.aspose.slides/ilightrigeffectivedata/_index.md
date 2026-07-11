---
title: ILightRigEffectiveData
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες του light rig.
type: docs
url: /el/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

Αμετάβλητο αντικείμενο που περιέχει τις αποτελεσματικές ιδιότητες του light rig.

--------------------

Αυτό το interface χρησιμοποιείται ως μέρος του [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση φωτός. |
| [getLightType()](#getLightType--) | Αντιπροσωπεύει ένα προκαθορισμένο light right που μπορεί να εφαρμοστεί σε ένα σχήμα. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται μέσω της χρήσης συντεταγμένης γεωβάλτιας, συντεταγμένης μήκους, και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωβάλτιας και μήκους. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Κατεύθυνση φωτός. Μόνο-ανάγνωση [LightingDirection](../../com.aspose.slides/lightingdirection).

**Επιστρέφει:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

Αντιπροσωπεύει ένα προκαθορισμένο light right που μπορεί να εφαρμοστεί σε ένα σχήμα. Το light rig αντιπροσωπεύει μια ομάδα φώτων προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Μόνο-ανάγνωση [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Επιστρέφει:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Μια περιστροφή ορίζεται μέσω της χρήσης συντεταγμένης γεωβάλτιας, συντεταγμένης μήκους, και μιας επανάληψης γύρω από τον άξονα όπως οι συντεταγμένες γεωβάλτιας και μήκους. Πρώτο στοιχείο στον πίνακα επιστροφής - γεωβάλτια, δεύτερο - μήκος, τρίτο - επανάληψη.

**Επιστρέφει:**
float[] - Συντεταγμένες περιστροφής ως float[]