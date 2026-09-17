---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions απαρίθμηση

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες δικαιώματα πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγεται με πρόσβαση χρήστη.

Ο τύπος PdfAccessPermissions εκθέτει τα ακόλουθα μέλη:

## Πεδία

| Πεδίο | Περιγραφή |
| :- | :- |
| NONE | Καθορίζει ότι ένας χρήστης δεν διαθέτει δικαιώματα πρόσβασης. |
| PRINT_DOCUMENT | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο (ενδεχομένως όχι στην υψηλότερη ποιότητα, ανάλογα με <br/>            αν το δυαδικό [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) είναι επίσης ορισμένο). |
| MODIFY_CONTENT | Καθορίζει αν ένας χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου με ενέργειες διαφορετικές από εκείνες που ελέγχονται<br/>            από τα δυαδικά [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Καθορίζει αν ένας χρήστης μπορεί να αντιγράψει ή να εξάγει με άλλον τρόπο κείμενο και γραφικά από το έγγραφο με ενέργειες <br/>            διαφορετικές από εκείνη που ελέγχεται από το δυαδικό [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Καθορίζει αν ένας χρήστης μπορεί να προσθέσει ή να τροποποιήσει σημειώσεις κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, αν το δυαδικό<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των <br/>            πεδίων υπογραφής). |
| FILL_EXISTING_FIELDS | Καθορίζει αν ένας χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη και αν<br/>            το δυαδικό [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) είναι καθαρό. |
| EXTRACT_TEXT_AND_GRAPHICS | Καθορίζει αν ένας χρήστης μπορεί να εξάγει κείμενο και γραφικά για υποστήριξη προσβασιμότητας σε χρήστες με αναπηρίες<br/>            ή για άλλους σκοπούς. |
| ASSEMBLE_DOCUMENT | Καθορίζει αν ένας χρήστης μπορεί να συγκροτήσει το έγγραφο (εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία σελιδοδεικτών ή<br/>            μικρογραφιών), ακόμη και αν το δυαδικό [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) είναι καθαρό. |
| HIGH_QUALITY_PRINT | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία μπορεί να παραχθεί πιστό ψηφιακό αντίγραφο του<br/>            περιεχομένου PDF. Όταν αυτό το δυαδικό είναι καθαρό (και το δυαδικό [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/el/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) είναι ορισμένο),<br/>            η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, πιθανώς με μειωμένη ποιότητα. |


### Δείτε επίσης
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)