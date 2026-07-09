---
title: SVGOptions
second_title: Aspose.Sildes για .NET – Αναφορά API
description: Αναπαριστά επιλογές SVG.
type: docs
weight: 4430
url: /el/aspose.slides.export/svgoptions/
---
## SVGOptions κλάση

Αναπαριστά επιλογές SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Κατασκευαστές

| Name | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης SVGOptions καθορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμων. |

## Ιδιότητες

| Name | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Επιστρέφει ρυθμίσεις για τη δημιουργία του απλούστερου και μικρότερου αρχείου SVG. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Επιστρέφει ρυθμίσεις για τη δημιουργία του πιο ακριβούς αρχείου SVG. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Ανάγνωση/Εγγραφή String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Σημαία Boolean που υποδεικνύει εάν τα περικομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Αν είναι true, τα περικομμένα τμήματα θα αφαιρεθούν· αν είναι false, θα σειριοποιηθούν στο έγγραφο (πράγμα που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/Εγγραφή Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνόλων χαρακτήρων (ligatures). Όταν οριστεί σε `true`, τα ligatures θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, η ιδιότητα είναι `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Απενεργοποιεί το διαχωρισμό των διαβαθμίσεων FromCornerX και FromCenter. Ανάγνωση/Εγγραφή Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Το SVG 1.1 δεν διαθέτει δυνατότητα καθορισμού εσωτερικών περιοχών για δείκτες. Η μηχανή εγγραφής Aspose.Slides SVG διαθέτει παράκαμψη: περικόπτει το άκρο της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τους δείκτες. Αυτή η επιλογή απενεργοποιεί τη συμπεριφορά αυτή. Ανάγνωση/Εγγραφή Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Καθορίζει τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/Εγγραφή [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/Εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση αντικειμένων Ink στο εξαχθέν έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/Εγγραφή Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Επιστρέφει ή ορίζει το κατώτατο όριο ανάλυσης για την απεικόνιση μετααρχείου. Ανάγνωση/Εγγραφή Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Παριστά το επίπεδο συμπίεσης των εικόνων. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Παριστά ένα αντικείμενο κλήσης επαναφοράς για αποθήκευση προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Επιστρέφει και ορίζει μια διεπαφή κλήσης επαναφοράς που επιτρέπει στο χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/Εγγραφή [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παραληφθούν υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/Εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/Εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/Εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Καθορίζει εάν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/Εγγραφή Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ματαιωθεί. Ανάγνωση/Εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διασύνδεση [ISVGOptions](../isvgoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->