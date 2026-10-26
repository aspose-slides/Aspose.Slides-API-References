---
title: ILightRig
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά LightRig.
type: docs
url: /el/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

Αναπαριστά LightRig.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Κατεύθυνση φωτός. |
| [setDirection(int value)](#setDirection-int-) | Κατεύθυνση φωτός. |
| [getLightType()](#getLightType--) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε σχήμα. |
| [setLightType(int value)](#setLightType-int-) | Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε σχήμα. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | Μια περιστροφή ορίζεται με χρήση συντεταγμένης latitude, συντεταγμένης longitude και επανάληψης γύρω από τον άξονα ως τις συντεταγμένες latitude και longitude. |
| [getRotation()](#getRotation--) | Μια περιστροφή ορίζεται με χρήση συντεταγμένης latitude, συντεταγμένης longitude και επανάληψης γύρω από τον άξονα ως τις συντεταγμένες latitude και longitude. |
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

Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε σχήμα. Το light rig αναπαριστά μια ομάδα φώτων προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Επιστρέφει:**  
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

Αναπαριστά μια προεπιλεγμένη δεξιά φωτεινή πηγή που μπορεί να εφαρμοστεί σε σχήμα. Το light rig αναπαριστά μια ομάδα φώτων προσανατολισμένων με συγκεκριμένο τρόπο σε σχέση με μια 3D σκηνή. Ανάγνωση/εγγραφή [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

Μια περιστροφή ορίζεται με χρήση συντεταγμένης latitude, συντεταγμένης longitude και επανάληψής γύρω από τον άξονα ως τις συντεταγμένες latitude και longitude.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| latitude | float | Συντεταγμένη latitude τύπου float |
| longitude | float | Συντεταγμένη longitude τύπου float |
| revolution | float | Συντεταγμένη revolution τύπου float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

Μια περιστροφή ορίζεται με χρήση συντεταγμένης latitude, συντεταγμένης longitude και επανάληψής γύρω από τον άξονα ως τις συντεταγμένες latitude και longitude. Το πρώτο στοιχείο στον πίνακα επιστροφής - latitude, το δεύτερο - longitude, το τρίτο - revolution.

**Επιστρέφει:**  
float[] - Συντεταγμένες περιστροφής ως float[]