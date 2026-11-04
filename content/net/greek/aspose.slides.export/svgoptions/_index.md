---
title: SVGOptions
second_title: Aspose.Sildes για .NET API Reference
description: Αναπαριστά επιλογές SVG.
type: docs
weight: 4450
url: /el/aspose.slides.export/svgoptions/
---
## κλάση SVGOptions

Represents an SVG options.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initializes a new instance of the SVGOptions class. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initializes a new instance of the SVGOptions class specifying the link embedding controller object. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο ανάγνωση [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Επιστρέφει ρυθμίσεις για τη πιο απλή και μικρότερη δημιουργία αρχείου SVG. Μόνο ανάγνωση [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Επιστρέφει ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείου SVG. Μόνο ανάγνωση [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Μία λογική σημαία που υποδεικνύει αν τα κομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι true τα κομμένα τμήματα θα αφαιρεθούν, εάν είναι false θα σειριοποιηθούν στο έγγραφο (το οποίο μπορεί ενδεχομένως να οδηγήσει σε μεγαλύτερο αρχείο). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Καθορίζει αν το κείμενο 3D είναι απενεργοποιημένο σε SVG. Ανάγνωση/εγγραφή Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Λαμβάνει ή ορίζει τιμή που υποδεικνύει αν το κείμενο αποτυπώνεται χωρίς χρήση ligatures. Όταν οριστεί σε `true`, τα ligatures θα απενεργοποιηθούν στην έξοδο απόδοσης. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Απενεργοποιεί το διαχωρισμό των gradient FromCornerX και FromCenter. Ανάγνωση/εγγραφή Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. Η μηχανή εγγραφής SVG της Aspose.Slides διαθέτει παρακάμματα για αυτό το πρόβλημα: κόβει το άκρο της γραμμής με το βέλος, ώστε η γραμμή να μην επικαλύπτει τους markers. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Καθορίζει έναν τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ του gradient. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Επιστρέφει ή ορίζει το όριο χαμηλής ανάλυσης για rasterization μετααρχείου. Ανάγνωση/εγγραφή Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Αναπαριστά το επίπεδο συμπίεσης εικόνων |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αναπαριστά ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στον χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει αν θα παραλείπεται οι υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Καθορίζει αν θα εκτελείται η καθορισμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Καθορίζει αν το πλαίσιο κειμένου θα περιλαμβάνεται σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Καθορίζει αν το κείμενο σε μια διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει αν η διαδικασία φόρτωσης θα συνεχιστεί ή θα τερματιστεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διεπαφή [ISVGOptions](../isvgoptions)
* χώρο ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->