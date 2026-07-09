---
title: SwfOptions
second_title: Aspose.Sildes για .NET API Reference
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Swf.
type: docs
weight: 4530
url: /el/aspose.slides.export/swfoptions/
---
## SwfOptions κλάση

Provides options that control how a presentation is saved in Swf format.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SwfOptions](swfoptions)() | Προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται εάν η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση-Εγγραφή String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. Η προεπιλογή είναι true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/Εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Εικόνα που θα εμφανιστεί ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG με διαστάσεις 32x64 εικονοστοιχεία, διαφορετικά το λογότυπο μπορεί να εμφανιστεί εσφαλμένα. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Αποκτά ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει καθοριστεί ένα [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Εμφανίζει/αποκρύπτει το κάτω τμήμα. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Εμφανίζει/αποκρύπτει το αριστερό τμήμα. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Καθορίζει εάν θα εμφανίζεται το πλαίσιο γύρω από τις σελίδες. Η προεπιλογή είναι true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Εμφανίζει/αποκρύπτει το βήμα σελίδας. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Εμφανίζει/αποκρύπτει ολόκληρο το επάνω τμήμα. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παραλείψετε υπερσυνδέσμους με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/Εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Ξεκινά με ανοιχτό αριστερό τμήμα. Μπορεί να παρακαμφθεί μέσω flashvars. Η προεπιλογή είναι false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο SWF θα περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλογή είναι `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί. Ανάγνωση/Εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε SWF Flash.

```csharp
[C#]
// Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Αποθήκευση παρουσίασης και σελίδων σημειώσεων
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διασύνδεση [ISwfOptions](../iswfoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->