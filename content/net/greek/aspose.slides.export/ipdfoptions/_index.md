---
title: IPdfOptions
second_title: Aspose.Sildes για .NET Αναφορά API
description: Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.
type: docs
weight: 4000
url: /el/aspose.slides.export/ipdfoptions/
---
## IPdfOptions διασύνδεση

Παρέχει επιλογές που ελέγχουν πώς μια παρουσίαση αποθηκεύεται σε μορφή Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης θα χορηγηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Επιστρέφει ή ορίζει έναν πίνακα με ονόματα γραμματοσειρών που καθορίζονται από το χρήστη, τα οποία η Aspose.Slides θα πρέπει να θεωρεί κοινά. Ανάγνωση/Εγγραφή String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Εφαρμόζει το καθορισμένο διαφανές χρώμα σε μια εικόνα εάν `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Επιστρέφει τη διεπαφή ISaveOptions. Μόνο για ανάγνωση [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Καθορίζει αν η πιο αποτελεσματική συμπίεση (αντί της προεπιλεγμένης) για κάθε εικόνα πρέπει να επιλέγεται αυτόματα. Εάν οριστεί σε Boolean.true, για κάθε εικόνα στην παρουσίαση θα επιλεγεί ο πιο κατάλληλος αλγόριθμος συμπίεσης, κάτι που θα οδηγήσει σε μικρότερο μέγεθος του παραγόμενου PDF εγγράφου. Η επιλογή του βέλτιστου λόγου συμπίεσης είναι υπολογιστικά ακριβή και απαιτεί επιπλέον RAM, ενώ αυτή η επιλογή είναι Boolean.false από προεπιλογή. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Επιθυμητό επίπεδο συμμόρφωσης για το παραγόμενο PDF έγγραφο. Ανάγνωση/Εγγραφή [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Αληθές για να σχεδιαστεί μαύρο πλαίσιο γύρω από κάθε διαφάνεια. Ανάγνωση/Εγγραφή Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Καθορίζει αν όλοι οι χαρακτήρες της γραμματοσειράς πρέπει να ενσωματωθούν ή μόνο το χρησιμοποιούμενο υποσύνολο. Ανάγνωση/Εγγραφή Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Αληθές για την ενσωμάτωση γραμματοσειρών TrueType για χαρακτήρες ASCII 32-127. Οι γραμματοσειρές για κωδικούς χαρακτήρων μεγαλύτερους από 127 ενσωματώνονται πάντα. Ανάγνωση/Εγγραφή Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Επιστρέφει ή ορίζει το διαφανές χρώμα της εικόνας. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση/Εγγραφή Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ποιότητα των εικόνων JPEG μέσα στο PDF έγγραφο. Ανάγνωση/Εγγραφή Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Ορισμός κωδικού πρόσβασης χρήστη για την προστασία του PDF εγγράφου. Ανάγνωση/Εγγραφή String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Καθορίζει αν το κείμενο πρέπει να ραστεροποιηθεί ως bitmap και να αποθηκευτεί στο PDF όταν η γραμματοσειρά δεν υποστηρίζει έντονη μορφή. Αυτή η προσέγγιση μπορεί να βελτιώσει την ποιότητα του κειμένου στο παραγόμενο PDF για ορισμένες γραμματοσειρές. Ανάγνωση/Εγγραφή Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Αληθές για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε παρουσίαση σε εικόνες PNG. Ανάγνωση/Εγγραφή Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Καθορίζει αν το παραγόμενο έγγραφο πρέπει να περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία με την οποία τοποθετούνται οι διαφάνειες στη σελίδα κατά την εξαγωγή μιας παρουσίασης [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Επιστρέφει ή ορίζει μια τιμή που καθορίζει την ανάλυση των εικόνων μέσα στο PDF έγγραφο. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Καθορίζει τον τύπο συμπίεσης που θα χρησιμοποιηθεί για όλο το κειμενικό περιεχόμενο στο έγγραφο. Ανάγνωση/Εγγραφή [`PdfTextCompression`](../pdftextcompression). |

### Δείτε επίσης

* διασύνδεση [ISaveOptions](../isaveoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->