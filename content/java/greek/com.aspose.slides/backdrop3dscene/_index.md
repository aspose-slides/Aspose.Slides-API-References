---
title: Backdrop3DScene
second_title: Aspose.Slides για Java Αναφορά API
description: Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.
type: docs
url: /el/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Ορίζει ένα επίπεδο στο οποίο εφαρμόζονται εφέ, όπως λάμψη και σκιά, σε σχέση με το σχήμα στο οποίο εφαρμόζονται.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Επιστρέφει ή ορίζει ένα κανονικό διάνυσμα. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Επιστρέφει ή ορίζει ένα κανονικό διάνυσμα. |
| [getAnchorPoint()](#getAnchorPoint--) | Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. |
| [getUpVector()](#getUpVector--) | Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση. |
| [setUpVector(float[] value)](#setUpVector-float---) | Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Έκδοση. Μόνο για ανάγνωση long.

**Επιστρέφει:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Επιστρέφει ή ορίζει ένα κανονικό διάνυσμα. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διάνυσμα που είναι κάθετο στην όψη του επίπεδου του παρασκηνίου. Διάνυσμα που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Επιστρέφει:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Επιστρέφει ή ορίζει ένα κανονικό διάνυσμα. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διάνυσμα που είναι κάθετο στην όψη του επίπεδου του παρασκηνίου. Διάνυσμα που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκυροβολεί το επίπεδο του παρασκηνίου. Σημείο 3D που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Επιστρέφει:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Επιστρέφει ή ορίζει ένα σημείο σε τρισδιάστατο χώρο. Αυτό το σημείο είναι το σημείο στο χώρο που αγκυροβολεί το επίπεδο του παρασκηνίου. Σημείο 3D που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση σε σχέση με την όψη του επίπεδου του παρασκηνίου. Διάνυσμα που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Επιστρέφει:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Επιστρέφει ή ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση. Πιο συγκεκριμένα, αυτή η ιδιότητα ορίζει ένα διάνυσμα που αντιπροσωπεύει την πάνω κατεύθυνση σε σχέση με την όψη του επίπεδου του παρασκηνίου. Διάνυσμα που αντιπροσωπεύεται από έναν πίνακα 3 τιμών τύπου float που ορίζουν τις συντεταγμένες X, Y και Z. Ανάγνωση/Εγγραφή float[].

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float[] |  |