---
title: TiffOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.
type: docs
weight: 4570
url: /el/aspose.slides.export/tiffoptions/
---
## TiffOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TiffOptions](tiffoptions)() | Προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Καθορίζει τον αλγόριθμο για τη μετατροπή μιας έγχρωμης εικόνας σε ασπρόμαυρη εικόνα. Αυτή η επιλογή θα εφαρμοστεί μόνο εάν [`CompressionType`](./compressiontype) είναι ορισμένο σε CCITT4 ή CCITT3 Ανάγνωση/εγγραφή [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Η προεπιλογή είναι Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Καθορίζει τον τύπο συμπίεσης. Ανάγνωση/εγγραφή [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται εάν η πηγή γραμματοσειράς δεν βρεθεί. Ανάγνωση-εγγραφή String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Καθορίζει την οριζόντια ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Καθορίζει την κάθετη ανάλυση σε κουκκίδες ανά ίντσα. Ανάγνωση/εγγραφή UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Καθορίζει το μέγεθος μιας παραγόμενης εικόνας TIFF. Η προεπιλεγμένη τιμή είναι 0x0, που σημαίνει ότι τα μεγέθη των παραγόμενων εικόνων θα υπολογιστούν βάσει του μεγέθους των διαφανειών της παρουσίασης. Ανάγνωση/εγγραφή Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Καθορίζει τη μορφή pixel για τις παραγόμενες εικόνες. Ανάγνωση/εγγραφή [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο θα περιέχει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε TIFF με προεπιλεγμένο μέγεθος.

```csharp
[C#]
// Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Αποθήκευση της παρουσίασης σε έγγραφο TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε TIFF με προσαρμοσμένο μέγεθος.

```csharp
[C#]
// Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Δημιουργήστε την κλάση TiffOptions
    TiffOptions opts = new TiffOptions();
    // Ορισμός τύπου συμπίεσης
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Τύποι συμπίεσης
    // Default - Καθορίζει το προεπιλεγμένο σχήμα συμπίεσης (LZW).
    // None - Καθορίζει καμία συμπίεση.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // Το βάθος εξαρτάται από τον τύπο συμπίεσης και δεν μπορεί να οριστεί χειροκίνητα.
    // Η μονάδα ανάλυσης είναι πάντα ίση με “2” (dots per inch)
    // Ρύθμιση DPI εικόνας
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Ορισμός μεγέθους εικόνας
    opts.ImageSize = new Size(1728, 1078);
    // Αποθήκευση της παρουσίασης σε TIFF με συγκεκριμένο μέγεθος εικόνας
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε TIFF με προσαρμοσμένη μορφή pixel εικόνας.

```csharp
[C#]
// Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat περιέχει τις ακόλουθες τιμές (όπως φαίνεται από την τεκμηρίωση):
    Format1bppIndexed; // 1 bit ανά pixel, ευρετηριασμένο.
    Format4bppIndexed; // 4 bits ανά pixel, ευρετηριασμένο.
    Format8bppIndexed; // 8 bits ανά pixel, ευρετηριασμένο.
    Format24bppRgb; // 24 bits ανά pixel, RGB.
    Format32bppArgb; // 32 bits ανά pixel, ARGB.
    */
    // Αποθήκευση της παρουσίασης σε TIFF με καθορισμένο μέγεθος εικόνας
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διασύνδεση [ITiffOptions](../itiffoptions)
* χώρος ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* σύγκροτηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->