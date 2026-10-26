---
title: get_InkEffectImages()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τη συλλογή των προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. Αυτές οι εικόνες χρησιμοποιούνται όταν γίνεται απόδοση της μελάνης με συγκεκριμένες τιμές InkEffectType, όπως Galaxy, Rainbow κ.ά. Παρέχοντας τις δικές σας εικόνες, μπορείτε να ελέγξετε πώς εμφανίζεται το κάθε εφέ μελάνης.
type: docs
weight: 14
url: /el/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() μέθοδος

Λαμβάνει τη συλλογή των προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης. Αυτές οι εικόνες χρησιμοποιούνται όταν γίνεται απόδοση της μελάνης με συγκεκριμένες [InkEffectType](../../inkeffecttype/) τιμές, όπως Galaxy, Rainbow κ.ά. Παρέχοντας τις δικές σας εικόνες, μπορείτε να ελέγξετε πώς εμφανίζεται το κάθε εφέ μελάνης.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```
## Παρατηρήσεις

Αυτή η ιδιότητα επιτρέπει την αντικατάσταση των προεπιλεγμένων υφισμάτων εφέ μελάνης με αυτά που ορίζονται από το χρήστη, κάτι που είναι ιδιαίτερα χρήσιμο όταν τα προεπιλεγμένα περιουσιακά στοιχεία περιορίζονται από άδειες ή δεν είναι διαθέσιμα κατά την εκτέλεση.

Κάθε καταχώρηση στο λεξικό πρέπει να συσχετίζει μια τιμή [InkEffectType](../../inkeffecttype/) με ένα αντίστοιχο αντικείμενο [IImage](../../../aspose.slides/iimage/) (π.χ., Bitmap ή μια διεπαφή εικόνας **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```
## Δείτε επίσης

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)