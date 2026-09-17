---
title: IBlobManagementOptions class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions κλάση

Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα που αποθηκεύονται ως μια ενιαία οντότητα - δηλαδή το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. Χρησιμοποιούνται διάφορες τεχνικές για τη βελτιστοποίηση της κατανάλωσης μνήμης κατά την εργασία με BLOBs - που ήταν ήδη αποθηκευμένα στην παρουσίαση ή προστέθηκαν μεταγενέστερα προγραμματικά. Χρησιμοποιώντας [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions) μπορείτε να αλλάξετε διαφορετικές πτυχές της συμπεριφοράς σχετικά με τη διαχείριση των BLOBs για τη διάρκεια ζωής του [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation).

Ο τύπος IBlobManagementOptions εκθέτει τα παρακάτω μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Αυτή η ιδιότητα ορίζει εάν ένα στιγμιότυπο της Presentation κλάση μπορεί να είναι ιδιοκτήτης του πηγαίου - αρχείου <br/>            ή ροής κατά τη διάρκεια ζωής του στιγμιότυπου. Εάν το στιγμιότυπο είναι ιδιοκτήτης, κλειδώνει το πηγαίο. Αυτό βοηθά <br/>            στη βελτίωση της κατανάλωσης μνήμης και της απόδοσης κατά την εργασία με BLOBs, αλλά το πηγαίο (ροή ή αρχείο) <br/>            δεν μπορεί να αλλάξει κατά τη διάρκεια ζωής του στιγμιότυπου του Presentation. Αυτό είναι ένα παράδειγμα: |
| [`is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Αυτή η ιδιότητα ορίζει εάν μπορούν να δημιουργηθούν προσωρινά αρχεία κατά την εργασία με BLOBs, κάτι που μειώνει σημαντικά τη κατανάλωση μνήμης αλλά απαιτεί άδειες για τη δημιουργία αρχείων.<br/>            Όλα τα αρχεία θα διαγραφούν μετά το τέλος της εργασίας με την παρουσίαση. |
| [`temp_files_root_path`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Η ριζική διαδρομή όπου θα δημιουργηθούν τα προσωρινά αρχεία. Ο φάκελος προσωρινών αρχείων του συστήματος θα χρησιμοποιηθεί εξ ορισμού. <br/>            Η διαδικασία φιλοξενίας πρέπει να έχει άδειες για <br/>            τη δημιουργία αρχείων και φακέλων εκεί. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Ορίζει το μέγιστο συνολικό μέγεθος (σε bytes) που μπορούν να καταλαμβάνουν όλα τα BLOBs στη μνήμη. Εξ ορισμού, όλα τα BLOBs<br/>            φορτώνονται στη μνήμη· μόνο όταν φτάσει αυτό το όριο χρησιμοποιούνται εναλλακτικοί μηχανισμοί (όπως προσωρινά<br/>            αρχεία). Η διατήρηση των BLOBs στη μνήμη μεγιστοποιεί την απόδοση αλλά μπορεί να οδηγήσει σε υψηλή χρήση μνήμης. Χρησιμοποιήστε<br/>            αυτή την ιδιότητα για να προσαρμόσετε τη συμπεριφορά στο περιβάλλον ή τις απαιτήσεις σας. |

### Δείτε επίσης
* κλάση [`IBlobManagementOptions`](/slides/python-net/el/aspose.slides/iblobmanagementoptions)
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)