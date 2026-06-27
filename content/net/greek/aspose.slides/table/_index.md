---
title: Table
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
type: docs
weight: 10840
url: /el/aspose.slides/table/
---
## Table κλάση

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα εμφανιστεί ένα σχήμα σε λειτουργία απλής λευκόμαυρης απεικόνισης. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Επιστρέφει τη συλλογή των στηλών. Read-only [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Read-only [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Επιστρέφει ένα αντικείμενο TableFormat.FillFormat που περιέχει τη διαμόρφωση γεμίσματος για το Table. Read-only [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Καθορίζει αν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική διαμόρφωση. Read/write Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Καθορίζει αν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική διαμόρφωση. Read/write Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος του σχήματος, μετρημένο σε points. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Read/write Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Καθορίζει αν οι άρτιες γραμμές πρέπει να σχεδιαστούν με διαφορετική διαμόρφωση. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τη διαχειριστική μονάδα υπερσυνδέσμων. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα του ποντικιού. Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Επιστρέφει ή ορίζει την επιλογή 'Mark as decorative'. Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Read-only Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Επιστρέφει το κελί στα καθορισμένα ευρετήρια στήλης και γραμμής. Read-only [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Καθορίζει αν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική διαμόρφωση. Read/write Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Καθορίζει αν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική διαμόρφωση. Read/write Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες διαμόρφωσης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Read-only UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει τον placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες πλαισίου του σχήματος. Read/write [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Καθορίζει αν ο πίνακας έχει σειρά ανάγνωσης δεξιά προς αριστερά. Read-write Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τον οποίο το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Read/write Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Επιστρέφει τη συλλογή των γραμμών. Read-only [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Read-only [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Επιστρέφει ή ορίζει το ενσωματωμένο στυλ πίνακα. Read/write [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες διαμόρφωσης για αυτόν τον πίνακα. Read-only [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν 3D ιδιότητες. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό αναγνωριστικό εντός παρουσίασης που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Read-only UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Καθορίζει αν οι άρτιες στήλες πρέπει να σχεδιαστούν με διαφορετική διαμόρφωση. Read/write Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του σχήματος, μετρημένο σε points. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του σχήματος, μετρημένο σε points. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην κλίμακα z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της κλίμακας z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός μέρος της κλίμακας z. Read-only Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder αν δεν υπάρχει και ορίζει τις ιδιότητες placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Επιστρέφει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδιδόμενο περιεχόμενο. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Συγχωνεύει γειτονικά κελιά. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφου σε όλες τις παραγράφους των κελιών του πίνακα. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμήματος σε όλα τα τμήματα των κελιών του πίνακα. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίου κειμένου σε όλα τα πλαίσια κειμένου των κελιών του πίνακα. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GraphicalObject](../graphicalobject)
* διασύνδεση [ITable](../itable)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->