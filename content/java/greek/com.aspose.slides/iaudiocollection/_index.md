---
title: IAudioCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή ενσωματωμένων αρχείων ήχου.
type: docs
url: /el/com.aspose.slides/iaudiocollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Represents a collection of embedded audio files.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Προσθέτει ένα αντίγραφο αρχείου ήχου από άλλη παρουσίαση. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από πίνακα byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Προσθέτει ένα αντίγραφο αρχείου ήχου από άλλη παρουσίαση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Πηγή ήχου. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί ήχος. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή από την οποία θα προστεθεί ήχος βίντεο. |
| loadingStreamBehavior | int | Το [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) που θα εφαρμοστεί στη ροή. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Δημιουργεί και προσθέτει ήχο σε μια παρουσίαση από πίνακα byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| audioData | byte[] | Bytes ήχου. |

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio) - Προστέθηκε ήχος.