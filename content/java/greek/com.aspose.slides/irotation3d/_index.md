---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: Αντιπροσωπεύει την 3D περιστροφή ενός διαγράμματος.
type: docs
url: /el/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Αντιπροσωπεύει την 3D περιστροφή ενός διαγράμματος.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRotationX()](#getRotationX--) | Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα X, δηλαδή |
| [setRotationX(byte value)](#setRotationX-byte-) | Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα X, δηλαδή |
| [getRotationY()](#getRotationY--) | Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα Y, δηλαδή |
| [setRotationY(int value)](#setRotationY-int-) | Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα Y, δηλαδή |
| [getPerspective()](#getPerspective--) | Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Καθορίζει αν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Καθορίζει αν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. |
| [getDepthPercents()](#getDepthPercents--) | Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). |
| [getHeightPercents()](#getHeightPercents--) | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα αντιστοιχεί στο στοιχείο 21.2.2.157 rotX (X Rotation) στην ECMA-376 και στην επιλογή "Y Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα X, δηλαδή στην κατεύθυνση Y για 3D διαγράμματα (μεταξύ -90 και 90 μοιρών). Η ιδιότητα αντιστοιχεί στο στοιχείο 21.2.2.157 rotX (X Rotation) στην ECMA-376 και στην επιλογή "Y Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα αντιστοιχεί στο στοιχείο 21.2.2.158 rotY (Y Rotation) στην ECMA-376 και στην επιλογή "X Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Επιστρέφει ή ορίζει τη γωνία περιστροφής γύρω από τον άξονα Y, δηλαδή στην κατεύθυνση X για 3D διαγράμματα (μεταξύ 0 και 360 μοιρών). Η ιδιότητα αντιστοιχεί στο στοιχείο 21.2.2.158 rotY (Y Rotation) στην ECMA-376 και στην επιλογή "X Rotation" στο PowerPoint 2007+. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 100). Αγνοείται εάν η τιμή της ιδιότητας RightAngleAxes είναι true. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

Επιστρέφει ή ορίζει την τιμή προοπτικής (γωνία οπτικού πεδίου) για 3D διαγράμματα (μεταξύ 0 και 100). Αγνοείται εάν η τιμή της ιδιότητας RightAngleAxes είναι true. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Καθορίζει αν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. Με άλλα λόγια, καθορίζει αν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή το υψόμετρο του διαγράμματος. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Καθορίζει αν οι άξονες του διαγράμματος είναι σε ορθές γωνίες, αντί να σχεδιάζονται σε προοπτική. Με άλλα λόγια, καθορίζει αν οι γωνίες των αξόνων του διαγράμματος είναι ανεξάρτητες από την περιστροφή ή το υψόμετρο του διαγράμματος. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

Επιστρέφει ή ορίζει το βάθος ενός 3D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 20 και 2000 τοις εκατό). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

Καθορίζει το ύψος ενός 3-D διαγράμματος ως ποσοστό του πλάτους του διαγράμματος (μεταξύ 5 και 500 τοις εκατό). Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |