---
title: SlideSize
second_title: Αναφορά API Aspose.Slides για Java
description: Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/slidesize/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Αναπαριστά το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSize()](#getSize--) | Παρέχει τις διαστάσεις της διαφάνειας σε points. |
| [getType()](#getType--) | Παρέχει τον τύπο μεγέθους της διαφάνειας. |
| [getOrientation()](#getOrientation--) | Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setOrientation(int value)](#setOrientation-int-) | Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Παρέχει τις διαστάσεις της διαφάνειας σε points.

--------------------

Η ανάθεση νέας τιμής επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

Παρέχει τον τύπο μεγέθους της διαφάνειας.

--------------------

Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize σύμφωνα με τις προκαθορισμένες διαστάσεις, διατηρώντας ταυτόχρονα τον τρέχοντα \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Η αλλαγή αυτής της τιμής ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Επιστρέφει:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Λαμβάνει ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Η αλλαγή αυτής της τιμής ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Το προκαθορισμένο μέγεθος διαφάνειας που θα εφαρμοστεί. |
| scaleType | int | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize βάσει του επιλεγμένου τύπου, διατηρώντας την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το νέο πλάτος της διαφάνειας, σε points. |
| height | float | Το νέο ύψος της διαφάνειας, σε points. |
| scaleType | int | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

--------------------

Αυτό επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |