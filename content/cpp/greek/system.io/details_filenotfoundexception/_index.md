---
title: Details_FileNotFoundException
second_title: Aspose.Slides για C++ API Αναφορά
description: "Η εξαίρεση που ρίχνεται όταν μια προσπάθεια πρόσβασης σε αρχείο που δεν υπάρχει στον δίσκο αποτυγχάνει. Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης με το χέρι. Χρησιμοποιήστε την κλάση FileNotFoundException αντ' αυτού. Ποτέ μην ενσωματώνετε τα στιγμιότυπα της κλάσης FileNotFoundException στο System::SmartPtr."
type: docs
weight: 183
url: /el/system.io/details_filenotfoundexception/
---
## Λεπτομέρειες_FileNotFoundException κλάση

Η εξαίρεση που ρίχνεται όταν μια προσπάθεια πρόσβασης σε αρχείο που δεν υπάρχει στον δίσκο αποτυγχάνει. Ποτέ μην δημιουργείτε στιγμιότυπα αυτής της κλάσης με το χέρι. Χρησιμοποιήστε την κλάση FileNotFoundException αντ' αυτού. Ποτέ μην ενσωματώνετε τα στιγμιότυπα της κλάσης FileNotFoundException στο [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Επιστρέφει το όνομα του αρχείου που προκαλεί αυτή την εξαίρεση. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Δείτε επίσης

* Κλάση [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Χώρος ονομάτων [System::IO](../)
* Βιβλιοθήκη [Aspose.Slides](../../)