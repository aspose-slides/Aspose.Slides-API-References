---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory ιδιότητα
Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Από προεπιλογή, όλα τα BLOBs φορτώνονται στη μνήμη· μόνο όταν επιτευχθεί αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή στις απαιτήσεις σας.

### Παρατηρήσεις
Αυτή η ιδιότητα παραβλέπεται εάν το [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) είναι ορισμένο σε false, καθώς η μνήμη είναι τότε η μοναδική διαθέσιμη τοποθεσία αποθήκευσης και ο περιορισμός της χρήσης των BLOB στη μνήμη δεν έχει καμία επίδραση.

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
* κλάση [`BlobManagementOptions`](/slides/python-net/el/aspose.slides/blobmanagementoptions)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)