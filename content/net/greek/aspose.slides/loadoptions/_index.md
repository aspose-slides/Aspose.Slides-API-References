---
title: LoadOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως μορφή ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
weight: 7840
url: /el/aspose.slides/loadoptions/
---
## LoadOptions κλάση

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφή ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

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
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό bytes BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να ορίσουν την καλύτερη σχέση απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μια ενιαία οντότητα - δηλαδή ένα BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Asian που χρησιμοποιείται στην περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται στην περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται στην περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Καθορίζει αν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθόλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Το διακριτικό για παρακολούθηση αιτημάτων διακοπής. Αυτό το διακριτικό διαχειρίζεται όλη τη διάρκεια ζωής του αντικειμένου [`IPresentation`](../ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση μιας παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [`Interrupt`](../interruptiontokensource/interrupt) του [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης προς φόρτωση. Ανάγνωση/εγγραφή [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι πρέπει να φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί. Η τιμή false σημαίνει ότι πρέπει να φορτωθεί ολόκληρη η κρυπτογραφημένη παρουσίαση με χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας παραβλέπεται πάντα. Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή είναι true, τότε οι ιδιότητες του εγγράφου δεν μπορούν να φορτωθούν και θα προκύψει εξαίρεση. Ανάγνωση/εγγραφή Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση/εγγραφή String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Επιστρέφει ή ορίζει τη διεπαφή callback που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Λαμβάνει επιλογές για λογιστικά φύλλα. Για παράδειγμα, αυτές οι επιλογές επηρεάζουν τον υπολογισμό τύπων για διαγράμματα. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* διεπαφή [ILoadOptions](../iloadoptions)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->