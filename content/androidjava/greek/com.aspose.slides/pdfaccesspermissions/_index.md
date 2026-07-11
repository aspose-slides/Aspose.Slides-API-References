---
title: PdfAccessPermissions
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποια δικαιώματα πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη.
type: docs
url: /el/com.aspose.slides/pdfaccesspermissions/
---
**Κληρονόμηση:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποια δικαιώματα πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [None](#None) | Καθορίζει ότι ο χρήστης δεν έχει δικαιώματα πρόσβασης. |
| [PrintDocument](#PrintDocument) | Καθορίζει εάν ο χρήστης μπορεί να εκτυπώσει το έγγραφο (ενδεχομένως όχι στο υψηλότερο επίπεδο ποιότητας, ανάλογα με το αν το δυαδικό [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) είναι επίσης ορισμένο). |
| [ModifyContent](#ModifyContent) | Καθορίζει εάν ο χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου με ενέργειες διαφορετικές από αυτές που ελέγχονται από τα δυαδικά [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Καθορίζει εάν ο χρήστης μπορεί να αντιγράψει ή να εξάγει κείμενο και γραφικά από το έγγραφο με ενέργειες διαφορετικές από αυτήν που ελέγχεται από το δυαδικό [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Καθορίζει εάν ο χρήστης μπορεί να προσθέσει ή να τροποποιήσει σχολιασμούς κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, εάν το δυαδικό [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής). |
| [FillExistingFields](#FillExistingFields) | Καθορίζει εάν ο χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμα και αν το δυαδικό [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) είναι απενεργοποιημένο. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Καθορίζει εάν ο χρήστης μπορεί να εξάγει κείμενο και γραφικά για να υποστηρίξει τη προσβασιμότητα σε χρήστες με αναπηρίες ή για άλλους σκοπούς. |
| [AssembleDocument](#AssembleDocument) | Καθορίζει εάν ο χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία σελιδοδεικτών ή μικρογραφιών), ακόμη και αν το δυαδικό [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι απενεργοποιημένο. |
| [HighQualityPrint](#HighQualityPrint) | Καθορίζει εάν ο χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία θα μπορούσε να παραχθεί μια ακριβής ψηφιακή αντίγραφο του περιεχομένου PDF. |
### Κανένα {#None}
```
public static final int None
```

Καθορίζει ότι ο χρήστης δεν έχει δικαιώματα πρόσβασης.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Καθορίζει εάν ο χρήστης μπορεί να εκτυπώσει το έγγραφο (ενδεχομένως όχι στο υψηλότερο επίπεδο ποιότητας, ανάλογα με το αν το δυαδικό [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) είναι επίσης ορισμένο).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Καθορίζει εάν ο χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου με ενέργειες διαφορετικές από αυτές που ελέγχονται από τα δυαδικά [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Καθορίζει εάν ο χρήστης μπορεί να αντιγράψει ή να εξάγει κείμενο και γραφικά από το έγγραφο με ενέργειες διαφορετικές από αυτήν που ελέγχεται από το δυαδικό [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Καθορίζει εάν ο χρήστης μπορεί να προσθέσει ή να τροποποιήσει σχολιασμούς κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, εάν το δυαδικό [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Καθορίζει εάν ο χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμα και αν το δυαδικό [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) είναι απενεργοποιημένο.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Καθορίζει εάν ο χρήστης μπορεί να εξάγει κείμενο και γραφικά για να υποστηρίξει τη προσβασιμότητα σε χρήστες με αναπηρίες ή για άλλους σκοπούς.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Καθορίζει εάν ο χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία σελιδοδεικτών ή μικρογραφιών), ακόμη και αν το δυαδικό [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι απενεργοποιημένο.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Καθορίζει εάν ο χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία θα μπορούσε να παραχθεί μια ακριβής ψηφιακή αντίγραφο του περιεχομένου PDF. Όταν αυτό το δυαδικό είναι απενεργοποιημένο (και το δυαδικό [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) είναι ορισμένο), η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, ενδεχομένως με μειωμένη ποιότητα.