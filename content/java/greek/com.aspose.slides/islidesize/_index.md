---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSize()](#getSize--) | Αποκτά τις διαστάσεις της διαφάνειας σε πόντους. |
| [getType()](#getType--) | Αποκτά τον τύπο μεγέθους της διαφάνειας. |
| [getOrientation()](#getOrientation--) | Αποκτά ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setOrientation(int value)](#setOrientation-int-) | Αποκτά ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ορίζει το μέγεθος της διαφάνειας με τύπο και κλιμακώνει το υπάρχον περιεχόμενο. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ορίζει τις διαστάσεις της διαφάνειας ρητά και κλιμακώνει το υπάρχον περιεχόμενο. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Αποκτά τις διαστάσεις της διαφάνειας σε πόντους.

--------------------

Η ανάθεση μιας νέας τιμής επαναφέρει την \#getType.getType property στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Αποκτά τον τύπο μεγέθους της διαφάνειας.

--------------------

Η ανάθεση οποιασδήποτε τιμής διαφορετικής από [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize σύμφωνα με τις προκαθορισμένες διαστάσεις, διατηρώντας ταυτόχρονα τον τρέχοντα \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Αποκτά ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτή τη τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Επιστρέφει:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Αποκτά ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτή τη τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Ορίζει το μέγεθος της διαφάνειας με τύπο και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Το προκαθορισμένο μέγεθος διαφάνειας που θα εφαρμοστεί. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Η ανάθεση οποιασδήποτε τιμής διαφορετικής από [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize βάσει του επιλεγμένου τύπου, διατηρώντας το \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Ορίζει τις διαστάσεις της διαφάνειας ρητά και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το νέο πλάτος της διαφάνειας, σε πόντους. |
| height | float | Το νέο ύψος της διαφάνειας, σε πόντους. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Αυτό επαναφέρει την \#getType.getType property στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει το \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |