---
title: PdfAccessPermissions
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/pdfaccesspermissions/
---
## PdfAccessPermissions κλάση

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη.

## Σταθερές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
[None](#None) | 0 | Καθορίζει ότι ένας χρήστης δεν έχει άδειες πρόσβασης. |
[PrintDocument](#PrintDocument) | 4 | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο (ενδεχομένως όχι στην υψηλότερη ποιότητα, ανάλογα με το αν το bit PdfAccessPermissions#HighQualityPrint είναι επίσης ορισμένο). |
[ModifyContent](#ModifyContent) | 8 | Καθορίζει αν ένας χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου μέσω λειτουργιών εκτός αυτών που ελέγχονται από τα bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument. |
[CopyTextAndGraphics](#CopyTextAndGraphics) | 16 | Καθορίζει αν ένας χρήστης μπορεί να αντιγράψει ή να εξαγάγει κείμενο και γραφικά από το έγγραφο μέσω λειτουργιών εκτός αυτής που ελέγχεται από το bit PdfAccessPermissions#ExtractTextAndGraphics. |
[AddOrModifyFields](#AddOrModifyFields) | 32 | Καθορίζει αν ένας χρήστης μπορεί να προσθέσει ή να τροποποιήσει σημειώσεις κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, εάν το bit PdfAccessPermissions#ModifyContent είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής). |
[FillExistingFields](#FillExistingFields) | 256 | Καθορίζει αν ένας χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη και αν το bit PdfAccessPermissions#AddOrModifyFields είναι μη ενεργό. |
[ExtractTextAndGraphics](#ExtractTextAndGraphics) | 512 | Καθορίζει αν ένας χρήστης μπορεί να εξάγει κείμενο και γραφικά για την υποστήριξη προσβασιμότητας σε χρήστες με αναπηρίες ή για άλλους σκοπούς. |
[AssembleDocument](#AssembleDocument) | 1024 | Καθορίζει αν ένας χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισάγοντας, περιστρέφοντας ή διαγράφοντας σελίδες και δημιουργώντας σελιδοδείκτες ή μικρογραφίες), ακόμη και αν το bit PdfAccessPermissions#ModifyContent είναι μη ενεργό. |
[HighQualityPrint](#HighQualityPrint) | 2048 | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία θα μπορούσε να δημιουργηθεί πιστό ψηφιακό αντίγραφο του περιεχομένου PDF. Όταν αυτό το bit είναι μη ενεργό (και το bit PdfAccessPermissions#PrintDocument είναι ορισμένο), η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, πιθανώς με μειωμένη ποιότητα. |

---

### None {#None}
Καθορίζει ότι ένας χρήστης δεν έχει άδειες πρόσβασης.

---

### PrintDocument {#PrintDocument}
Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο (ενδεχομένως όχι στην υψηλότερη ποιότητα, ανάλογα με το αν το bit PdfAccessPermissions#HighQualityPrint είναι επίσης ορισμένο).

---

### ModifyContent {#ModifyContent}
Καθορίζει αν ένας χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου μέσω λειτουργιών εκτός αυτών που ελέγχονται από τα bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument.

---

### CopyTextAndGraphics {#CopyTextAndGraphics}
Καθορίζει αν ένας χρήστης μπορεί να αντιγράψει ή να εξαγάγει κείμενο και γραφικά από το έγγραφο μέσω λειτουργιών εκτός αυτής που ελέγχεται από το bit PdfAccessPermissions#ExtractTextAndGraphics.

---

### AddOrModifyFields {#AddOrModifyFields}
Καθορίζει αν ένας χρήστης μπορεί να προσθέσει ή να τροποποιήσει σημειώσεις κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, εάν το bit PdfAccessPermissions#ModifyContent είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής).

---

### FillExistingFields {#FillExistingFields}
Καθορίζει αν ένας χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη και αν το bit PdfAccessPermissions#AddOrModifyFields είναι μη ενεργό.

---

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
Καθορίζει αν ένας χρήστης μπορεί να εξάγει κείμενο και γραφικά για την υποστήριξη προσβασιμότητας σε χρήστες με αναπηρίες ή για άλλους σκοπούς.

---

### AssembleDocument {#AssembleDocument}
Καθορίζει αν ένας χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισάγοντας, περιστρέφοντας ή διαγράφοντας σελίδες και δημιουργώντας σελιδοδείκτες ή μικρογραφίες), ακόμη και αν το bit PdfAccessPermissions#ModifyContent είναι μη ενεργό.

---

### HighQualityPrint {#HighQualityPrint}
Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία θα μπορούσε να δημιουργηθεί πιστό ψηφιακό αντίγραφο του περιεχομένου PDF. Όταν αυτό το bit είναι μη ενεργό (και το bit PdfAccessPermissions#PrintDocument είναι ορισμένο), η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, πιθανώς με μειωμένη ποιότητα.

---