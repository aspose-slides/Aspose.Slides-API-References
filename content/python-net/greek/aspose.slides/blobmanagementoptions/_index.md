---
title: BlobManagementOptions class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions κλάση

Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση των κανόνων χειρισμού BLOB και άλλων ρυθμίσεων BLOB.

Ο τύπος BlobManagementOptions εκθέτει τα ακόλουθα μέλη:

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [`__init__(self)`](/slides/python-net/el/aspose.slides/blobmanagementoptions/__init__/#) | Δημιουργεί νέες προεπιλεγμένες επιλογές διαχείρισης blob. |

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/el/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Αυτή η ιδιότητα καθορίζει εάν ένα στιγμιότυπο της κλάσης Presentation μπορεί να είναι ιδιοκτήτης του αρχείου πηγής ή ροής κατά τη διάρκεια της ζωής του στιγμιότυπου. Εάν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει την πηγή. Αυτό βοηθά στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOB, αλλά η πηγή (ροή ή αρχείο) δεν μπορεί να αλλάξει κατά τη διάρκεια της ζωής του στιγμιότυπου Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Αυτή η ιδιότητα καθορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOB, πράγμα που μειώνει σημαντικά την κατανάλωση μνήμης αλλά απαιτεί δικαιώματα δημιουργίας αρχείων. Όλα τα αρχεία θα διαγραφούν μετά την ολοκλήρωση της εργασίας με την παρουσίαση. |
| [`temp_files_root_path`](/slides/python-net/el/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο προεπιλεγμένος προσωρινός κατάλογος του συστήματος θα χρησιμοποιηθεί. Η διαδικασία φιλοξενίας πρέπει να έχει δικαιώματα δημιουργίας αρχείων και φακέλων εκεί. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/el/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Ορίζει το μέγιστο συνολικό μέγεθος (σε byte) που μπορούν να καταλαμβάνουν όλα τα BLOB στη μνήμη. Προεπιλογή, όλα τα BLOB φορτώνονται στη μνήμη· μόνο όταν επιτευχθεί αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά αρχεία). Η διατήρηση των BLOB στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε αυτήν την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)