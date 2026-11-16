---
title: SwfOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Swf.
type: docs
weight: 4550
url: /el/aspose.slides.export/swfoptions/
---
## SwfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SwfOptions](swfoptions)() | Προκαθορισμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να συμπιεστεί ή όχι. Η προεπιλογή είναι `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. String με δυνατότητα ανάγνωση/εγγραφή. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Ενεργοποίηση/απενεργοποίηση μενού περιβάλλοντος. Η προεπιλογή είναι `true`. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλογή είναι 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG 32x64 pixel, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Ανακτά ή ορίζει τη πλήρη διεύθυνση υπερσυνδέσμου για ένα λογότυπο. Έχει αποτέλεσμα μόνο εάν έχει οριστεί ένα [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο callback για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Εμφάνιση/απόκρυψη του κάτω πάνελ. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Εμφάνιση/απόκρυψη του κουμπιού πλήρους οθόνης. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Εμφάνιση/απόκρυψη του αριστερού πάνελ. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Καθορίζει αν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλογή είναι `true`. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Εμφάνιση/απόκρυψη του μεταβλητή σελίδας. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Εμφάνιση/απόκρυψη της ενότητας αναζήτησης. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Εμφάνιση/απόκρυψη ολόκληρου του επάνω πάνελ. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `true`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει αν θα παραλειφθούν οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Boolean με δυνατότητα ανάγνωση/εγγραφή. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [`HandoutLayoutingOptions`](../handoutlayoutingoptions) |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Ξεκινά με ανοικτό το αριστερό πάνελ. Μπορεί να αντικατασταθεί στα flashvars. Η προεπιλογή είναι `false`. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Καθορίζει αν το παραγόμενο έγγραφο SWF πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφων ή όχι. Η προεπιλογή είναι `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Ανακτά ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε SWF Flash.

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
* διεπαφή [ISwfOptions](../iswfoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->