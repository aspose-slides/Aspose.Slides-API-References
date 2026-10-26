---
title: PresentationLockingBehavior
second_title: Aspose.Sildes για PHP μέσω αναφοράς Java API
description: 
type: docs

url: /el/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior κλάση

Αντιπροσωπεύει τη συμπεριφορά σχετικά με τη διαχείριση της πηγής IPresentation (αρχείο ή java.io.InputStream) κατά τη φόρτωση και εργασία με ένα αντίτυπο του IPresentation. Η πηγή είναι η παράμετρος που περνιέται στον κατασκευαστή IPPresentation. Στο παρακάτω παράδειγμα, η πηγή είναι το αρχείο "pres.pptx": Για αυτό το παράδειγμα, η πηγή (αρχείο "pres.pptx") θα παραμείνει κλειδωμένη για όλη τη διάρκεια ζωής ενός αντικειμένου IPPresentation, δηλαδή δεν μπορεί να αλλαχθεί ή να διαγραφεί από άλλη διαδικασία.

## Σταθερές

| Name | Value | Description |
| --- | --- | --- |
[LoadAndRelease](#LoadAndRelease) | 0 | Η πηγή θα παραμείνει κλειδωμένη μόνο για τη διάρκεια εκτέλεσης του κατασκευαστή IPPresentation. Εάν ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) έχει οριστεί σε false, όλα τα BLOB θα φορτωθούν στη μνήμη. Διαφορετικά, μπορεί να χρησιμοποιηθούν άλλα μέσα όπως προσωρινά αρχεία. Αυτή η συμπεριφορά είναι πιο αργή από PresentationLockingBehavior#KeepLocked και, εάν είναι δυνατόν να μεταβιβαστεί η ιδιοκτησία της πηγής στο IPPresentation, συνιστάται η χρήση του PresentationLockingBehavior#KeepLocked. |
[KeepLocked](#KeepLocked) | 1 | Η πηγή θα παραμείνει κλειδωμένη για ολόκληρη τη διάρκεια ζωής ενός αντικειμένου IPPresentation, μέχρι να τεθεί σε διακοπή. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) πρέπει να οριστεί σε true για τη χρήση αυτής της συμπεριφοράς, διαφορετικά θα εξαχθεί μια εξαίρεση. Αυτή η συμπεριφορά συνιστάται, είναι ταχύτερη και καταναλώνει λιγότερη μνήμη από PresentationLockingBehavior#LoadAndRelease. |

---

### LoadAndRelease {#LoadAndRelease}
Η πηγή θα παραμείνει κλειδωμένη μόνο για τη διάρκεια εκτέλεσης του κατασκευαστή IPPresentation. Εάν ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) έχει οριστεί σε false, όλα τα BLOB θα φορτωθούν στη μνήμη. Διαφορετικά, μπορεί να χρησιμοποιηθούν άλλα μέσα όπως προσωρινά αρχεία. Αυτή η συμπεριφορά είναι πιο αργή από PresentationLockingBehavior#KeepLocked και, εάν είναι δυνατόν να μεταβιβαστεί η ιδιοκτησία της πηγής στο IPPresentation, συνιστάται η χρήση του PresentationLockingBehavior#KeepLocked.

---

### KeepLocked {#KeepLocked}
Η πηγή θα παραμείνει κλειδωμένη για ολόκληρη τη διάρκεια ζωής ενός αντικειμένου IPPresentation, μέχρι να τεθεί σε διακοπή. IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) πρέπει να οριστεί σε true για τη χρήση αυτής της συμπεριφοράς, διαφορετικά θα εξαχθεί μια εξαίρεση. Αυτή η συμπεριφορά συνιστάται, είναι ταχύτερη και καταναλώνει λιγότερη μνήμη από PresentationLockingBehavior#LoadAndRelease.

---