---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior απαρίθμηση

Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη μεταχείριση της πηγής [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation) (αρχείο ή **io.RawIOBase**) κατά τη φόρτωση και εργασία με μια παρουσία του [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation).

Ο τύπος PresentationLockingBehavior εκθέτει τα παρακάτω μέλη:

## Πεδία

| Πεδίο | Περιγραφή |
| :- | :- |
| LOAD_AND_RELEASE | Η πηγή θα κλειδωθεί μόνο για τη διάρκεια της εκτέλεσης του κατασκευαστή [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation).<br/>            Αν το [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) οριστεί σε false, όλα τα BLOB θα φορτωθούν στη μνήμη. Διαφορετικά, μπορεί να χρησιμοποιηθούν άλλοι τρόποι όπως προσωρινά αρχεία. Αυτή η συμπεριφορά είναι πιο αργή από το [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/el/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), και αν είναι δυνατόν να περάσει η ιδιοκτησία της πηγής στο [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation), συνιστάται η χρήση του [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/el/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Η πηγή θα κλειδωθεί για ολόκληρη τη διάρκεια ζωής του αντικειμένου [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation), μέχρι να διαγραφεί.<br/>            Το [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/el/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) πρέπει να οριστεί σε true για τη χρήση αυτής της συμπεριφοράς, διαφορετικά θα προκληθεί εξαίρεση. Αυτή η συμπεριφορά συνιστάται, είναι πιο γρήγορη και καταναλώνει λιγότερη μνήμη από το [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/el/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |


### Παρατηρήσεις

Η πηγή είναι η παράμετρος που περνιέται στον κατασκευαστή [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation). Στο παρακάτω παράδειγμα, η πηγή είναι το αρχείο "pres.pptx":

Για αυτό το παράδειγμα, η πηγή (αρχείο "pres.pptx") θα κλειδωθεί για τη διάρκεια ζωής του αντικειμένου [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation), δηλαδή δεν μπορεί να τροποποιηθεί ή να διαγραφεί από άλλη διεργασία.


### Δείτε επίσης
* κλάση [`IPresentation`](/slides/python-net/el/aspose.slides/ipresentation)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)