---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /el/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ, όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Επιστρέφει ή ορίζει ένα διάνυσμα κανονικής. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Επιστρέφει ή ορίζει ένα διάνυσμα κανονικής. |
| [getAnchorPoint()](#getAnchorPoint--) | Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. |
| [getUpVector()](#getUpVector--) | Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση. |
| [setUpVector(float[] value)](#setUpVector-float---) | Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Επιστρέφει ή ορίζει ένα διάνυσμα κανονικής. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα κάθετο στην όψη του επιπέδου υποβάθρου. Το διάνυσμα αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/εγγραφή float[].

**Επιστρέφει:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Επιστρέφει ή ορίζει ένα διάνυσμα κανονικής. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα κάθετο στην όψη του επιπέδου υποβάθρου. Το διάνυσμα αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμές X, Y και Z. Ανάγνωση/εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκυροβολεί το επίπεδο υποβάθρου. Το σημείο 3D αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/εγγραφή float[].

**Επιστρέφει:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκυροβολεί το επίπεδο υποβάθρου. Το σημείο 3D αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση σε σχέση με την όψη του επιπέδου υποβάθρου. Το διάνυσμα αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/εγγραφή float[].

**Επιστρέφει:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση. Πιο συγκεκριμένα, αυτό το χαρακτηριστικό ορίζει ένα διάνυσμα που αντιπροσωπεύει την άνω κατεύθυνση σε σχέση με την όψη του επιπέδου υποβάθρου. Το διάνυσμα αναπαρίσταται από πίνακα 3 τιμών float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |