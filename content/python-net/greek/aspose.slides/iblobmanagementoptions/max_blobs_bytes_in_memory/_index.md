---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory ιδιότητα
Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που όλα τα BLOBs μπορούν να καταλάβουν στη μνήμη. Από προεπιλογή, όλα τα BLOBs
            φορτώνονται στη μνήμη· μόνο όταν φτάσει αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά
            αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας.

### Παρατηρήσεις

Αυτή η ιδιότητα παραβλέπεται εάν [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) οριστεί σε false, καθώς η μνήμη είναι τότε
            η μόνη διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης BLOB στη μνήμη δεν έχει κανένα αποτέλεσμα.

### Ορισμός:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)