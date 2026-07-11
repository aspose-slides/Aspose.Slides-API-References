---
title: Rotation3D
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει την 3D περιστροφή ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/rotation3d/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Αντιπροσωπεύει την 3D περιστροφή ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRotationX()](#getRotationX--) | Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή |
| [setRotationX(byte value)](#setRotationX-byte-) | Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή |
| [getRotationY()](#getRotationY--) | Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή |
| [setRotationY(int value)](#setRotationY-int-) | Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή |
| [getPerspective()](#getPerspective--) | Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Καθορίζει εάν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Καθορίζει εάν οι άξονες του διαγράμματα είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. |
| [getDepthPercents()](#getDepthPercents--) | Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). |
| [getHeightPercents()](#getHeightPercents--) | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```


Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```


Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.157 rotX (X Rotation) στο ECMA-376 και με την επιλογή "Y Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```


Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```


Επιστρέφει ή ορίζει το βαθμό περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα ταιριάζει με το στοιχείο 21.2.2.158 rotY (Y Rotation) στο ECMA-376 και με την επιλογή "X Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```


Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 240). Αγνοείται εάν η τιμή της ιδιότητας RightAngleAxes είναι true. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```


Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 240). Αγνοείται εάν η τιμή της ιδιότητας RightAngleAxes είναι true. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```


Καθορίζει εάν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. Με άλλα λόγια, καθορίζει εάν οι γωνίες των αξόνων είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```


Καθορίζει εάν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. Με άλλα λόγια, καθορίζει εάν οι γωνίες των αξόνων είναι ανεξάρτητες από την περιστροφή ή την ανύψωση του διαγράμματος. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```


Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```


Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```


Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```


Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject