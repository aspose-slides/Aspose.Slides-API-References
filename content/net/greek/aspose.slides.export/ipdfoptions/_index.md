---
title: IPdfOptions
second_title: Aspose.Sildes για .NET API Αναφορά
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PDF.
type: docs
weight: 4020
url: /el/aspose.slides.export/ipdfoptions/
---
## IPdfOptions διασύνδεση

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή PDF.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να χορηγούνται όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα οικογενειών γραμματοσειρών που ορίζονται από το χρήστη, τις οποίες το Aspose.Slides θα πρέπει να θεωρεί κοινές. Ανάγνωση/εγγραφή String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Επιστρέφει τη διασύνδεση ISaveOptions. Μόνο για ανάγνωση [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Δηλώνει εάν η πιο αποτελεσματική συμπίεση (αντί για την προεπιλεγμένη) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε Boolean.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του τελικού εγγράφου PDF. Η επιλογή του βέλτιστου λόγου συμπίεσης εικόνας είναι υπολογιστικά ακριβή και απαιτεί πρόσθετη μνήμη RAM, και αυτή η επιλογή είναι Boolean.false από προεπιλογή. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Επιθυμητό επίπεδο συμμόρφωσης για το δημιουργούμενο έγγραφο PDF. Ανάγνωση/εγγραφή [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Ορισμός true για να σχεδιάζεται μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Καθορίζει εάν όλα τα χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο ένα υποσύνολο. Ανάγνωση/εγγραφή Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Ορισμός true για ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Ανάγνωση/εγγραφή Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Ανακτά ή ορίζει το διαφανές χρώμα της εικόνας. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Ορισμός true για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο τελικό PDF. Ανάγνωση/εγγραφή Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο έγγραφο PDF. Ανάγνωση/εγγραφή Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Ορίζει κωδικό πρόσβασης χρήστη για την προστασία του εγγράφου PDF. Ανάγνωση/εγγραφή String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Δηλώνει εάν το κείμενο πρέπει να ραστεριστεί ως bitmap και να αποθηκευτεί σε PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο τελικό PDF για ορισμένες γραμματοσειρές. Ανάγνωση/εγγραφή Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Ορισμός true για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Καθορίζει εάν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Ανακτά ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο έγγραφο PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/εγγραφή [`PdfTextCompression`](../pdftextcompression). |

### Δείτε επίσης

* διασύνδεση [ISaveOptions](../isaveoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->