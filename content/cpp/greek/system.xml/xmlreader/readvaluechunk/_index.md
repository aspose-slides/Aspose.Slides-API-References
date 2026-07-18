---
title: ReadValueChunk()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαβάζει μεγάλες ροές κειμένου ενσωματωμένες σε ένα έγγραφο XML.
type: docs
weight: 807
url: /el/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) μέθοδος


Διαβάζει μεγάλες ροές κειμένου ενσωματωμένες σε ένα έγγραφο XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Ο πίνακας χαρακτήρων που λειτουργεί ως ενδιάμεση μνήμη στην οποία γράφεται το κείμενο. Αυτή η τιμή δεν μπορεί να είναι **nullptr**. |
| index | **int32_t** | Η μετατόπιση εντός της ενδιάμεσης μνήμης όπου το [XmlReader](../) μπορεί να αρχίσει να αντιγράφει τα αποτελέσματα. |
| count | **int32_t** | Ο μέγιστος αριθμός χαρακτήρων που θα αντιγραφούν στην ενδιάμεση μνήμη. Ο πραγματικός αριθμός των αντιγραμμένων χαρακτήρων επιστρέφεται από αυτή τη μέθοδο. |

### Τιμή Επιστροφής

Ο αριθμός των χαρακτήρων που διαβήθηκαν στην ενδιάμεση μνήμη. Η τιμή μηδέν επιστρέφεται όταν δεν υπάρχει άλλο κείμενο.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Τάξη [XmlReader](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)