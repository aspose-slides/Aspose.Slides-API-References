---
title: IImage
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει μια ραστροειδής ή διανυσματική εικόνα.
type: docs
url: /el/com.aspose.slides/iimage/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Αναπαριστά μια ραστροειδής ή διανυσματική εικόνα.

--------------------

Αυτή η διεπαφή παρέχει μια κοινή αφαίρεση για τη διαχείριση τόσο ραστροειδών όσο και διανυσματικών εικόνων. Οι υλοποιήσεις μπορεί να διαφέρουν ανάλογα με τον υποκείμενο τύπο εικόνας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Αποθηκεύει την εικόνα σε ένα αρχείο. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή και ποιότητα. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή και ποιότητα. |
| [getSize()](#getSize--) | Επιστρέφει το μέγεθος της εικόνας. |
| [getWidth()](#getWidth--) | Επιστρέφει το πλάτος της εικόνας σε εικονοστοιχεία. |
| [getHeight()](#getHeight--) | Επιστρέφει το ύψος της εικόνας σε εικονοστοιχεία. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Αποθηκεύει την εικόνα σε ένα αρχείο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | int | Η μορφή της εικόνας. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | int | Η μορφή της εικόνας. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


Αποθηκεύει την εικόνα σε ένα αρχείο στη συγκεκριμένη μορφή και ποιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Η διαδρομή προς το αρχείο όπου θα αποθηκευτεί η εικόνα. |
| format | int | Η μορφή της εικόνας. |
| quality | int | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100). Αυτή η παράμετρος επηρεάζει μόνο την αποθήκευση σε [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)· για όλες τις άλλες μορφές, αγνοείται. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


Αποθηκεύει την εικόνα σε μια ροή στη συγκεκριμένη μορφή και ποιότητα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή όπου θα αποθηκευτεί η εικόνα. |
| format | int | Η μορφή της εικόνας. |
| quality | int | Η ποιότητα της αποθηκευμένης εικόνας (0 έως 100). Αυτή η παράμετρος επηρεάζει μόνο την αποθήκευση σε [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg)· για όλες τις άλλες μορφές, αγνοείται. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```


Επιστρέφει το μέγεθος της εικόνας.

**Επιστρέφει:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Επιστρέφει το πλάτος της εικόνας σε εικονοστοιχεία.

**Επιστρέφει:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Επιστρέφει το ύψος της εικόνας σε εικονοστοιχεία.

**Επιστρέφει:**
int