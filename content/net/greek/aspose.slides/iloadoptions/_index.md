---
title: ILoadOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Επιτρέπει τον καθορισμό πρόσθετων επιλογών, όπως μορφή ή προεπιλεγμένη γραμματοσειρά, κατά τη φόρτωση μιας παρουσίασης.
type: docs
weight: 6360
url: /el/aspose.slides/iloadoptions/
---
## ILoadOptions διασύνδεση

Allows to specify additional options (such as format or default font) when loading a presentation.

```csharp
public interface ILoadOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τη διαχείριση της συμπεριφοράς χειρισμού Binary Large Objects (BLOBs), όπως η χρήση προσωρινών αρχείων ή το μέγιστο αριθμό byte BLOB στη μνήμη. Αυτές οι επιλογές προορίζονται να θέσουν το καλύτερο λόγο απόδοσης/χρήσης μνήμης για ένα συγκεκριμένο περιβάλλον ή απαιτήσεις. Ένα Binary Large Object (BLOB) είναι δυαδικά δεδομένα που αποθηκεύονται ως μία ενιαία οντότητα - δηλαδή το BLOB μπορεί να είναι ήχος, βίντεο ή η ίδια η παρουσίαση. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Επιστρέφει ή ορίζει τη γλώσσα γραμματοσειράς Asian που χρησιμοποιείται σε περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Ανάγνωση-εγγραφή String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται όταν η πηγή γραμματοσειράς δεν βρεθεί. Ανάγνωση-εγγραφή String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά Symbol που χρησιμοποιείται όταν η πηγή γραμματοσειράς δεν βρεθεί. Ανάγνωση-εγγραφή String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Επιστρέφει ή ορίζει την προεπιλεγμένη γλώσσα για το κείμενο της παρουσίασης. Ανάγνωση/εγγραφή String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Καθορίζει εάν το Aspose.Slides θα διαγράψει όλα τα ενσωματωμένα δυαδικά αντικείμενα κατά τη φόρτωση της παρουσίασης. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Καθορίζει τις πηγές για εξωτερικές γραμματοσειρές που θα χρησιμοποιηθούν από την παρουσίαση. Αυτές οι γραμματοσειρές είναι διαθέσιμες στην παρουσίαση καθ' όλη τη διάρκεια ζωής της και δεν μοιράζονται με άλλες παρουσιάσεις |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Το token για την παρακολούθηση αρχών διακοπής. Αυτό το token διαχειρίζεται ολόκληρη τη διάρκεια ζωής του αντικειμένου [`IPresentation`](../ipresentation). Οποιαδήποτε μακρά λειτουργία, όπως η φόρτωση ή η αποθήκευση παρουσίασης, θα διακοπεί μέσω κλήσης της μεθόδου [`Interrupt`](../iinterruptiontokensource/interrupt) του [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Επιστρέφει ή ορίζει τη μορφή μιας παρουσίασης για φόρτωση. Ανάγνωση/εγγραφή [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Αυτή η ιδιότητα είναι χρήσιμη όταν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό πρόσβασης. Η τιμή true σημαίνει ότι μόνο οι ιδιότητες του εγγράφου πρέπει να φορτωθούν από κρυπτογραφημένο αρχείο παρουσίασης και ο κωδικός πρέπει να αγνοηθεί. Η τιμή false σημαίνει ότι ολόκληρη η κρυπτογραφημένη παρουσίαση πρέπει να φορτωθεί με τη χρήση του σωστού κωδικού. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας παραβλέπεται πάντα. Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες και η τιμή της ιδιότητας είναι true, τότε οι ιδιότητες του εγγράφου δεν μπορούν να φορτωθούν και θα προκληθεί εξαίρεση. Ανάγνωση-εγγραφή Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Λαμβάνει ή ορίζει τον κωδικό πρόσβασης. Ανάγνωση-εγγραφή String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Επιστρέφει ή ορίζει τη διεπαφή επιστροφής κλήσης που διαχειρίζεται τη φόρτωση εξωτερικών πόρων. Ανάγνωση/εγγραφή [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Αντιπροσωπεύει τις επιλογές που μπορούν να χρησιμοποιηθούν για τον καθορισμό πρόσθετης συμπεριφοράς των λογιστικών φύλλων. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* χώροςσυνολο [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->