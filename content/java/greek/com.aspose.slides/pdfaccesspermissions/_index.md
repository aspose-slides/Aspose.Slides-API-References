---
title: PdfAccessPermissions
second_title: Aspose.Slides για την αναφορά API Java
description: Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιές άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη.
type: docs
url: /el/com.aspose.slides/pdfaccesspermissions/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιές άδειες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [None](#None) | Καθορίζει ότι ένας χρήστης δεν έχει άδειες πρόσβασης. |
| [PrintDocument](#PrintDocument) | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο (πιθανώς όχι στο υψηλότερο επίπεδο ποιότητας, ανάλογα αν το bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) είναι επίσης ορισμένο). |
| [ModifyContent](#ModifyContent) | Καθορίζει αν ένας χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου μέσω λειτουργιών διαφορετικών από αυτές που ελέγχονται από τα bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Καθορίζει αν ένας χρήστης μπορεί να αντιγράψει ή να εξάγει κείμενο και γραφικά από το έγγραφο μέσω λειτουργιών διαφορετικών από αυτή που ελέγχεται από το bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Καθορίζει αν ένας χρήστης μπορεί να προσθέσει ή να τροποποιήσει σημειώσεις κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, αν το bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής). |
| [FillExistingFields](#FillExistingFields) | Καθορίζει αν ένας χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη κι αν το bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) δεν είναι ορισμένο. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Καθορίζει αν ένας χρήστης μπορεί να εξάγει κείμενο και γραφικά για την υποστήριξη προσβασιμότητας σε χρήστες με αναπηρίες ή για άλλους σκοπούς. |
| [AssembleDocument](#AssembleDocument) | Καθορίζει αν ένας χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία σελιδοδεικτών ή μικρογραφιών), ακόμη κι αν το bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) δεν είναι ορισμένο. |
| [HighQualityPrint](#HighQualityPrint) | Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία μπορεί να δημιουργηθεί μια πιστή ψηφιακή αντίγραφο του περιεχομένου PDF. |
### None {#None}
```
public static final int None
```


Καθορίζει ότι ένας χρήστης δεν έχει άδειες πρόσβασης.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο (πιθανώς όχι στο υψηλότερο επίπεδο ποιότητας, ανάλογα αν το bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) είναι επίσης ορισμένο).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Καθορίζει αν ένας χρήστης μπορεί να τροποποιήσει το περιεχόμενο του εγγράφου μέσω λειτουργιών διαφορετικών από αυτές που ελέγχονται από τα bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


Καθορίζει αν ένας χρήστης μπορεί να αντιγράψει ή να εξάγει κείμενο και γραφικά από το έγγραφο μέσω λειτουργιών διαφορετικών από αυτή που ελέγχεται από το bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


Καθορίζει αν ένας χρήστης μπορεί να προσθέσει ή να τροποποιήσει σημειώσεις κειμένου, να συμπληρώσει διαδραστικά πεδία φόρμας και, αν το bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) είναι επίσης ορισμένο, να δημιουργήσει ή να τροποποιήσει διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


Καθορίζει αν ένας χρήστης μπορεί να συμπληρώσει υπάρχοντα διαδραστικά πεδία φόρμας (συμπεριλαμβανομένων των πεδίων υπογραφής), ακόμη κι αν το bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) δεν είναι ορισμένο.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


Καθορίζει αν ένας χρήστης μπορεί να εξάγει κείμενο και γραφικά για την υποστήριξη προσβασιμότητας σε χρήστες με αναπηρίες ή για άλλους σκοπούς.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Καθορίζει αν ένας χρήστης μπορεί να συναρμολογήσει το έγγραφο (εισαγωγή, περιστροφή ή διαγραφή σελίδων και δημιουργία σελιδοδεικτών ή μικρογραφιών), ακόμη κι αν το bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) δεν είναι ορισμένο.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


Καθορίζει αν ένας χρήστης μπορεί να εκτυπώσει το έγγραφο σε μια αναπαράσταση από την οποία μπορεί να δημιουργηθεί μια πιστή ψηφιακή αντίγραφο του περιεχομένου PDF. Όταν αυτό το bit δεν είναι ορισμένο (και το bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) είναι ορισμένο), η εκτύπωση περιορίζεται σε μια χαμηλού επιπέδου αναπαράσταση της εμφάνισης, πιθανώς με μειωμένη ποιότητα.