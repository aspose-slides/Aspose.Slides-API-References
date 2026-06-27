---
title: SwfOptions
second_title: Αναφορά API του Aspose.Sildes για .NET
description: Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή Swf.
type: docs
weight: 4510
url: /el/aspose.slides.export/swfoptions/
---
## SwfOptions κλάση

Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή Swf.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο SWF θα πρέπει να είναι συμπιεσμένο ή όχι. Η προεπιλεγμένη τιμή είναι `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. String με δυνατότητα ανάγνωσης/εγγραφής. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Ενεργοποιεί/απενεργοποιεί το μενού περιβάλλοντος. Η προεπιλεγμένη τιμή είναι true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα των εικόνων JPEG. Η προεπιλεγμένη τιμή είναι 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Εικόνα που θα εμφανίζεται ως λογότυπο στην επάνω δεξιά γωνία του προβολέα. Η εικόνα πρέπει να είναι PNG με διαστάσεις 32x64 pixels, διαφορετικά το λογότυπο μπορεί να εμφανιστεί λανθασμένα. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Επιστρέφει ή ορίζει τη πλήρη διεύθυνση υπερ-σύνδεσμου για ένα λογότυπο. Έχει αντίκτυπο μόνο εάν έχει οριστεί ένα [`LogoImageBytes`](./logoimagebytes). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο callback για την αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Εμφανίζει/αποκρύπτει το κάτω τμήμα. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Εμφανίζει/αποκρύπτει το κουμπί πλήρους οθόνης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλεγμένη τιμή είναι `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Εμφανίζει/αποκρύπτει το αριστερό τμήμα. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Καθορίζει εάν θα εμφανίζεται το περίγραμμα γύρω από τις σελίδες. Η προεπιλεγμένη τιμή είναι true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Εμφανίζει/αποκρύπτει το κουμπί αλλαγής σελίδας. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Εμφανίζει/αποκρύπτει την ενότητα αναζήτησης. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Εμφανίζει/αποκρύπτει ολόκληρο το πάνω τμήμα. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παρακάμπτει τα υπερ-σύνδεσμους με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Boolean ανάγνωση/εγγραφή. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). Αυτή η ιδιότητα δεν υποστηρίζει την ανάθεση αντικειμένων τύπου [`HandoutLayoutingOptions`](../handoutlayoutingoptions). |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Ξεκινά με ανοιχτό αριστερό τμήμα. Μπορεί να αντικατασταθεί μέσω flashvars. Η προεπιλεγμένη τιμή είναι false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο SWF θα πρέπει να περιλαμβάνει τον ενσωματωμένο προβολέα εγγράφου ή όχι. Η προεπιλεγμένη τιμή είναι `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί. [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) με δυνατότητα ανάγνωσης/εγγραφής. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε PowerPoint σε SWF Flash.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Αποθήκευση της παρουσίασης και των σελίδων σημειώσεων
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διασύνδεση [ISwfOptions](../iswfoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->