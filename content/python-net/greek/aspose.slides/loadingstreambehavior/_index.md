---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior απαριθμός

Το **io.RawIOBase** που περνιέται σε μια μέθodu θεωρείται ως Binary Large Object (BLOB) (δείτε την περιγραφή του [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions)). Οι τιμές αυτού του απαριθμού καθορίζουν πώς πρέπει να αντιμετωπιστεί το **io.RawIOBase** όταν περνιέται στη μέθodu. Ανάλογα με τις απαιτήσεις, μπορούν να ληφθούν διαφορετικές αποφάσεις για να παρασχεθεί η πιο αποδοτική συμπεριφορά.

Ο τύπος LoadingStreamBehavior εκθέτει τα ακόλουθα μέλη:

## Πεδία

| Πεδίο | Περιγραφή |
| :- | :- |
| READ_STREAM_AND_RELEASE | Η ροή θα διαβαστεί μέχρι το τέλος και στη συνέχεια θα απελευθερωθεί - δηλαδή θα είναι εγγυημένο ότι αυτή η ροή <br/> δεν θα χρησιμοποιηθεί από την παρουσία [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) στο μέλλον. Μπορεί να κλείσει από τον κώδικα του πελάτη <br/> ή να χρησιμοποιηθεί με οποιονδήποτε άλλο τρόπο. |
| KEEP_LOCKED | Η ροή θα κλειδωθεί μέσα στο αντικείμενο [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation), δηλαδή η κυριότητα της <br/> ροής θα μεταφερθεί. Το αντικείμενο [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) θα είναι υπεύθυνο για <br/> τη σωστή διαχείριση της ροής όταν αυτό το αντικείμενο θα διαγραφεί το ίδιο. <br/> Αυτή η συμπεριφορά είναι εξαιρετικά χρήσιμη όταν χρειάζεται να σειριοποιήσετε ένα μεγάλο αρχείο BLOB (όπως ένα μεγάλο <br/> βίντεο ή ήχο - δείτε την περιγραφή του [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions)) και θέλετε να αποτρέψετε τη φόρτωση <br/> αυτού του αρχείου στη μνήμη ή άλλα προβλήματα απόδοσης. Μπορείτε απλώς να ανοίξετε το **System.IO.FileStream** <br/> για αυτό το αρχείο και να το περάσετε σε μια μέθodu, επιλέγοντας [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/el/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Δείτε επίσης
* κλάση [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions)
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)