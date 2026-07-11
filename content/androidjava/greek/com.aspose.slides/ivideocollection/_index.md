---
title: IVideoCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά μια συλλογή αντικειμένων Video.
type: docs
url: /el/com.aspose.slides/ivideocollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Αναπαριστά μια συλλογή αντικειμένων Video.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Προσθέτει ένα αντίγραφο αρχείου βίντεο από άλλη παρουσίαση. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από ροή. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από πίνακα byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IVideo](../../com.aspose.slides/ivideo).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Προσθέτει ένα αντίγραφο αρχείου βίντεο από άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Πηγή βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Βίντεο που προστέθηκε.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί το αρχείο βίντεο. |
| loadingStreamBehavior | int | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστέθηκε [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από πίνακα byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| videoData | byte[] | Bytes βίντεο. |

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo) - Προστέθηκε βίντεο.