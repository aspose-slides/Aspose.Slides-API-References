---
title: SVGOptions
second_title: Aspose.Sildes για .NET API Reference
description: Αναπαριστά επιλογές SVG.
type: docs
weight: 4410
url: /el/aspose.slides.export/svgoptions/
---
## SVGOptions κλάση

Αναπαριστά επιλογές SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SVGOptions, καθορίζοντας το αντικείμενο ελεγκτή ενσωμάτωσης συνδέσμου ILinkEmbedController. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Επιστρέφει τις προεπιλεγμένες ρυθμίσεις. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Επιστρέφει ρυθμίσεις για την απλούστερη και μικρότερη δημιουργία αρχείων SVG. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Επιστρέφει ρυθμίσεις για τη πιο ακριβή δημιουργία αρχείων SVG. Μόνο για ανάγνωση [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν η πηγαία γραμματοσειρά δεν βρεθεί. Ανάγνωση/εγγραφή String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Σημαία boolean που υποδεικνύει εάν τα κομμένα τμήματα παραμένουν ως μέρος του εγγράφου. Εάν είναι true τα κομμένα τμήματα θα αφαιρεθούν, εάν είναι false θα σειριοποιηθούν στο έγγραφο (που μπορεί να οδηγήσει σε μεγαλύτερο αρχείο). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Καθορίζει εάν το 3D κείμενο είναι απενεργοποιημένο στο SVG. Ανάγνωση/εγγραφή Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Λαμβάνει ή ορίζει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων (ligatures). Όταν οριστεί σε `true`, οι συνδέσεις θα απενεργοποιηθούν στο αποδοθέν αποτέλεσμα. Από προεπιλογή, αυτή η ιδιότητα είναι `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Απενεργοποιεί τη διάσπαση των gradient FromCornerX και FromCenter. Ανάγνωση/εγγραφή Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | Το SVG 1.1 δεν διαθέτει δυνατότητα ορισμού εσοχών για markers. Η μηχανή εγγραφής Aspose.Slides SVG έχει παράκαμψη: κόβει το τέλος της γραμμής με βέλος, ώστε η γραμμή να μην επικαλύπτει τα markers. Αυτή η επιλογή απενεργοποιεί αυτή τη συμπεριφορά. Ανάγνωση/εγγραφή Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Καθορίζει τον τρόπο διαχείρισης εξωτερικά φορτωμένων γραμματοσειρών. Ανάγνωση/εγγραφή [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Επιστρέφει ή ορίζει το οπτικό στυλ του gradient. Ανάγνωση/εγγραφή [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο. Μόνο για ανάγνωση [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Καθορίζει την ποιότητα κωδικοποίησης JPEG. Ανάγνωση/εγγραφή Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Επιστρέφει ή ορίζει το κατώτερο όριο ανάλυσης για την rasterization μετααρχείου. Ανάγνωση/εγγραφή Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Αναπαριστά το επίπεδο συμπίεσης των εικόνων |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Αναπαριστά ένα αντικείμενο callback για αποθήκευση ενημερώσεων προόδου σε ποσοστό. Δείτε [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Επιστρέφει και ορίζει μια διεπαφή callback που επιτρέπει στο χρήστη να ελέγχει τη μετατροπή σχήματος. Ανάγνωση/εγγραφή [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Καθορίζει εάν θα παραλείπονται οι υπερσύνδεσμοι με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Καθορίζει εάν θα εκτελεστεί η συγκεκριμένη περιστροφή του σχήματος κατά την απόδοση ή όχι. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Καθορίζει εάν το πλαίσιο κειμένου θα συμπεριληφθεί σε περιοχή απόδοσης ή όχι. Ανάγνωση/εγγραφή Boolean. Η προεπιλεγμένη τιμή είναι false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Καθορίζει εάν το κείμενο σε διαφάνεια θα αποθηκευτεί ως γραφικά. Ανάγνωση/εγγραφή Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Δείτε επίσης

* κλάση [SaveOptions](../saveoptions)
* διεπαφή [ISVGOptions](../isvgoptions)
* χώρος ονομάτων [Aspose.Slides.Export](../../aspose.slides.export)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->