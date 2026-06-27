---
title: LoadOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Διευκολύνει τον καθορισμό πρόσθετων επιλογών, όπως μορφή ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
weight: 7820
url: /el/aspose.slides/loadoptions/
---
## LoadOptions κλάση

Δημιουργεί τη δυνατότητα καθορισμού επιπλέον επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

```csharp
public class LoadOptions : ILoadOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Δημιουργεί νέες προεπιλεγμένες επιλογές φόρτωσης. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Δημιουργεί νέες επιλογές φόρτωσης. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB σε μνήμη. Αυτές οι επιλογές προορίζονται για τον καθορισμό του βέλτιστου λόγου απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως ενιαία οντότητα - π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Επιστρέφει ή ορίζει την ασιατική γραμματοσειρά που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη συνηθισμένη γραμματοσειρά που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Καθορίζει τις πηγές για τις εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής. Αυτό το διακριτικό διαχειρίζεται ολόκληρη τη διάρκεια ζωής της διεργασίας [`IPresentation`](../ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση της παρουσίασης, θα διακοπεί με την κλήση της μεθόδου [`Interrupt`](../interruptiontokensource/interrupt) του [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου πρέπει να φορτωθούν από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί. Η τιμή false σημαίνει ότι πρέπει να φορτωθεί ολόκληρη η κρυπτογραφημένη παρουσίαση με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας παραβλέπεται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα προκληθεί εξαίρεση. Ανάγνωση/εγγραφή Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Επιστρέφει ή ορίζει τη διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Λαμβάνει τις επιλογές για λογιστικά φύλλα. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για γραφήματα. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* διασύνδεση [ILoadOptions](../iloadoptions)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->