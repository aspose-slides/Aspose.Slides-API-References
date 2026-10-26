---
title: ILoadOptions
second_title: Aspose.Sildes για .NET Αναφορά API
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως μορφοποίηση ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
weight: 6340
url: /el/aspose.slides/iloadoptions/
---
## ILoadOptions διεπαφή

Επιτρέπει τον καθορισμό πρόσθετων επιλογών (όπως μορφοποίηση ή προεπιλεγμένη γραμματοσειρά) κατά τη φόρτωση μιας παρουσίασης.

```csharp
public interface ILoadOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς επεξεργασίας Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό byte BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να ρυθμίσουν τον καλύτερο λόγο απόδοσης/κατανάλωσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα αποθηκευμένα ως μια ενιαία οντότητα - π.χ. το BLOB μπορεί να είναι ήχος, βίντεο ή η παρουσίαση αυτή καθαυτή. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Επιστρέφει ή ορίζει την Ασιατική γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη κανονική (Regular) γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν δεν βρεθεί η πηγή γραμματοσειράς. Ανάγνωση-εγγραφή String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Επιστρέφει ή ορίζει τη προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Καθορίζει αν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις. |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Το διακριτικό για την παρακολούθηση αιτημάτων διακοπής. Αυτό το διακριτικό διαχειρίζεται ολόκληρο το χρόνο ζωής του παραδείγματος [`IPresentation`](../ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση της παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [`Interrupt`](../iinterruptiontokensource/interrupt) του [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Επιστρέφει ή ορίζει τη μορφή παρουσίασης που θα φορτωθεί. Ανάγνωση/εγγραφή [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό. Η τιμή true σημαίνει ότι θα φορτωθούν μόνο οι ιδιότητες του εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός θα αγνοηθεί. Η τιμή false σημαίνει ότι η πλήρης κρυπτογραφημένη παρουσίαση θα φορτωθεί με τη χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας αγνοείται πάντα. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε οι ιδιότητες εγγράφου δεν μπορούν να φορτωθούν και θα πεταχτεί εξαίρεση. Ανάγνωση-εγγραφή Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Αποκτά ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση-εγγραφή String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Επιστρέφει ή ορίζει τη διεπαφή επανάκλησης (callback) που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για να καθοριστεί η συμπεριφορά πρόσθετων λογιστικών φύλλων. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* χωρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->