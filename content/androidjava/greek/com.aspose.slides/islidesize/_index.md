---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSize()](#getSize--) | Λαμβάνει τις διαστάσεις της διαφάνειας σε μονάδες points. |
| [getType()](#getType--) | Λαμβάνει τον τύπο μεγέθους της διαφάνειας. |
| [getOrientation()](#getOrientation--) | Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setOrientation(int value)](#setOrientation-int-) | Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Λαμβάνει τις διαστάσεις της διαφάνειας σε μονάδες points.

--------------------

Η ανάθεση μιας νέας τιμής επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

Λαμβάνει τον τύπο μεγέθους της διαφάνειας.

--------------------

Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize σύμφωνα με τις προεπιλεγμένες διαστάσεις, διατηρώντας τον τρέχοντα \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτήν την τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Επιστρέφει:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτήν την τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο προεπιλεγμένος τύπος διαφάνειας που θα εφαρμοστεί. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize βάσει του επιλεγμένου τύπου, διατηρώντας το \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το νέο πλάτος της διαφάνειας, σε μονάδες points. |
| height | float | Το νέο ύψος της διαφάνειας, σε μονάδες points. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Αυτό επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει το \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |