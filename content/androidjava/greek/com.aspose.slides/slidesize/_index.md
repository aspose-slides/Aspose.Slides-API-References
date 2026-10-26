---
title: SlideSize
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
type: docs
url: /el/com.aspose.slides/slidesize/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Αντιπροσωπεύει το μέγεθος και τον προσανατολισμό μιας διαφάνειας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSize()](#getSize--) | Ανακτά τις διαστάσεις της διαφάνειας σε μονάδες point. |
| [getType()](#getType--) | Ανακτά τον τύπο μεγέθους της διαφάνειας. |
| [getOrientation()](#getOrientation--) | Ανακτά ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setOrientation(int value)](#setOrientation-int-) | Ανακτά ή ορίζει τον προσανατολισμό της διαφάνειας. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ορίζει το μέγεθος της διαφάνειας με βάση τον τύπο και κλιμακώνει το υπάρχον περιεχόμενο. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ορίζει τις διαστάσεις της διαφάνειας ρητά και κλιμακώνει το υπάρχον περιεχόμενο. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Ανακτά τις διαστάσεις της διαφάνειας σε μονάδες point.

--------------------

Η ανάθεση μιας νέας τιμής επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Ανακτά τον τύπο μεγέθους της διαφάνειας.

--------------------

Η εκχώρηση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize σύμφωνα με τις προκαθορισμένες διαστάσεις, διατηρώντας τον τρέχοντα \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Επιστρέφει:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Ανακτά ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτήν την τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Επιστρέφει:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Ανακτά ή ορίζει τον προσανατολισμό της διαφάνειας.

--------------------

Αλλάζοντας αυτήν την τιμή ανταλλάσσει το πλάτος και το ύψος της διαφάνειας.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Ορίζει το μέγεθος της διαφάνειας με βάση τον τύπο και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο προρυθμισμένος τύπος διαφάνειας που θα εφαρμοστεί. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί.

--------------------

Η εκχώρηση οποιασδήποτε τιμής εκτός του [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) προσαρμόζει το \#getSize.getSize βάσει του επιλεγμένου τύπου, διατηρώντας το \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |
### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Ορίζει τις διαστάσεις της διαφάνειας ρητά και κλιμακώνει το υπάρχον περιεχόμενο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | float | Το νέο πλάτος της διαφάνειας, σε μονάδες point. |
| height | float | Το νέο ύψος της διαφάνειας, σε μονάδες point. |
| scaleType | int | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί.

--------------------

Αυτό επαναφέρει την ιδιότητα \#getType.getType στο [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) και ορίζει την \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |