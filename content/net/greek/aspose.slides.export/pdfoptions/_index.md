---
title: PdfOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.
type: docs
weight: 4350
url: /el/aspose.slides.export/pdfoptions/
---
## PdfOptions κλάση

Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default constructor. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες δικαιοδοσίες πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών ορισμένα από τον χρήστη, που το Aspose.Slides θα θεωρήσει κοινά. Ανάγνωση/Εγγραφή String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Δείχνει εάν η πιο αποτελεσματική συμπίεση (αντί για την προεπιλεγμένη) για κάθε εικόνα πρέπει να επιλεχθεί αυτόματα. Εάν οριστεί σε Boolean.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου εγγράφου PDF. Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά απαιτητική και καταναλώνει πρόσθετη μνήμη RAM, και αυτή η επιλογή είναι Boolean.false από προεπιλογή. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο έγγραφο PDF. Ανάγνωση/Εγγραφή [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/Εγγραφή String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True για να σχεδιάσει μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Ανάγνωση/Εγγραφή Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Καθορίζει εάν όλα τα χαρακτήρα της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιημένο υποσύνολο. Ανάγνωση/Εγγραφή Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Καθορίζει εάν το Aspose.Slides θα ενσωματώνει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κώδικα 33..127). Οι γραμματοσειρές για κώδικες χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και πρόσθετες γραμματοσειρές που ορίζονται από τον χρήστη. Ανάγνωση/Εγγραφή Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της μετάπτωσης. Ανάγνωση/Εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Λαμβάνει ή ορίζει το διαφανές χρώμα της εικόνας. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True για να μετατρέψει όλα τα δεδομένα OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/Εγγραφή Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαχθέν έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. Ανάγνωση/Εγγραφή Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/Εγγραφή String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο κλήσης επιστροφής για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Δείχνει εάν το κείμενο πρέπει να ρεϋσταριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονο στυλ. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/Εγγραφή Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True για να μετατρέψει όλα τα μετααρχεία που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/Εγγραφή Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν να παραληφθούν οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/Εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο του εγγράφου. Ανάγνωση/Εγγραφή [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/Εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με προσαρμοσμένες επιλογές.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Δημιουργεί την κλάση PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ορίζει την ποιότητα JPEG
	pdfOptions.JpegQuality = 90;
	// Ορίζει τη συμπεριφορά για μετααρχεία
	pdfOptions.SaveMetafilesAsPng = true;
	// Ορίζει το επίπεδο συμπίεσης κειμένου
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Ορίζει το πρότυπο PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Αποθηκεύει την παρουσίαση ως PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με κρυφές διαφάνειες.

```csharp
[C#]
// Δημιουργεί μια κλάση Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Δημιουργεί την κλάση PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Προσθέτει κρυφές διαφάνειες
	pdfOptions.ShowHiddenSlides = true;
	// Αποθηκεύει την παρουσίαση ως PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF προστατευμένο με κωδικό.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Δημιουργεί την κλάση PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ορίζει κωδικό πρόσβασης PDF και δικαιώματα πρόσβασης
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Αποθηκεύει την παρουσίαση ως PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Το ακόλουθο παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με σημειώσεις.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Ορισμός τύπου διαφάνειας και μεγέθους
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διεπαφή [IPdfOptions](../ipdfoptions)
* χώρος ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->