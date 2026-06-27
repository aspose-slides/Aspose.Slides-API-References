---
title: PdfOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.
type: docs
weight: 4310
url: /el/aspose.slides.export/pdfoptions/
---
## PdfOptions κλάση

Provides options that control how a presentation is saved in Pdf format.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Κατασκευαστές

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default constructor. |

## Ιδιότητες

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Περιέχει ένα σύνολο σημάνσεων που καθορίζουν ποιες δικαιώματα πρόσβασης πρέπει να χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Επιστρέφει ή ορίζει έναν πίνακα ονομάτων οικογενειών γραμματοσειρών που ορίζονται από τον χρήστη, τις οποίες το Aspose.Slides πρέπει να θεωρεί κοινές. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Εφαρμόζει το καθορισμένο διαυγές χρώμα σε μια εικόνα εάν `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε Boolean.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του τελικού εγγράφου PDF. Η επιλογή της βέλτιστης αναλογίας συμπίεσης εικόνας είναι υπολογιστικά δαπανηρή και απαιτεί πρόσθετη μνήμη RAM, και αυτή η επιλογή είναι Boolean.false από προεπιλογή. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργημένο έγγραφο PDF. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγαία γραμματοσειρά δεν βρεθεί. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True για να σχεδιάζεται μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Καθορίζει εάν όλα τα χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο που χρησιμοποιείται. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Καθορίζει εάν το Aspose.Slides θα ενσωματώσει κοινές γραμματοσειρές για κείμενο ASCII (εύρος κωδίκων 33..127). Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Η λίστα κοινών γραμματοσειρών περιλαμβάνει τις 14 βασικές γραμματοσειρές του PDF και πρόσθετες γραμματοσειρές που ορίζονται από το χρήστη. Read/write Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Αποκτά ή ορίζει το διαυγές χρώμα της εικόνας. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True για να μετατρέπονται όλα τα δεδομένα OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. Read/write Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Read/write String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αντιπροσωπεύει ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Δηλώνει εάν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφοποίηση. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True για να μετατραπούν όλα τα metafiles που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το δημιουργημένο έγγραφο πρέπει να συμπεριλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Read/write Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Αποκτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Read/write [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα διακοπεί. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με προσαρμοσμένες επιλογές.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Δημιουργεί ένα αντικείμενο της κλάσης PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ορίζει την ποιότητα Jpeg
	pdfOptions.JpegQuality = 90;
	// Ορίζει τη συμπεριφορά για τα metafiles
	pdfOptions.SaveMetafilesAsPng = true;
	// Ορίζει το επίπεδο συμπίεσης κειμένου
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Καθορίζει το πρότυπο PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Αποθηκεύει την παρουσίαση ως PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με κρυφές διαφάνειες.

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

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF προστατευμένο με κωδικό.

```csharp
[C#]
// Δημιουργεί ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Δημιουργεί την κλάση PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ορίζει τον κωδικό πρόσβασης PDF και τα δικαιώματα πρόσβασης
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Αποθηκεύει την παρουσίαση ως PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να μετατρέψετε το PowerPoint σε PDF με σημειώσεις.

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
* διασύνδεση [IPdfOptions](../ipdfoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->