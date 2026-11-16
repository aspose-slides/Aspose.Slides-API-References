---
title: Table
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει έναν πίνακα σε μια διαφάνεια.
type: docs
weight: 10880
url: /el/aspose.slides/table/
---
## κλάση Table

Represents a table on a slide.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρου. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Επιστρέφει τη συλλογή των στηλών. Μόνο ανάγνωση [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Επιστρέφει ένα αντικείμενο TableFormat.FillFormat που περιέχει τη μορφοποίηση γεμίσματος για τον Πίνακα. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Καθορίζει εάν η πρώτη στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Καθορίζει εάν η πρώτη γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυμμένο. Ανάγνωση/εγγραφή Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Καθορίζει εάν οι ζυγές γραμμές πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Επιστρέφει το κελί στα καθορισμένα ευρετήρια στήλης και γραμμής. Μόνο ανάγνωση [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Καθορίζει εάν η τελευταία στήλη ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Καθορίζει εάν η τελευταία γραμμή ενός πίνακα πρέπει να σχεδιαστεί με ειδική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στο διαφάνεια, το οποίο παραμένει σταθερό κατά τη διάρκεια της ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape αν το σχήμα είναι ομαδοποιημένο. Διαφορεμένα επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Καθορίζει εάν ο πίνακας έχει σειρά ανάγνωσης από δεξιά προς αριστερά. Ανάγνωση/εγγραφή Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Επιστρέφει τη συλλογή των γραμμών. Μόνο ανάγνωση [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ιδιότητες) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Λαμβάνει ή ορίζει το ενσωματωμένο στυλ πίνακα. Ανάγνωση/εγγραφή [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Επιστρέφει το αντικείμενο TableFormat που περιέχει τις ιδιότητες μορφοποίησης για αυτόν τον πίνακα. Μόνο ανάγνωση [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που παρέχει ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες 3D. Μόνο ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναπροσαρμοστεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Καθορίζει εάν οι ζυγές στήλες πρέπει να σχεδιαστούν με διαφορετική μορφοποίηση. Ανάγνωση/εγγραφή Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει την x-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει την y-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην σειρά z. Shapes[0] επιστρέφει το σχήμα στο τέλος της σειράς z, ενώ Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στην αρχή της σειράς z. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια-μητέα από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape για τα όρια της μικρογραφίας χρησιμοποιείται εξ' ορισμού. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο περιεχόμενό του. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Συγχωνεύει γειτονικά κελιά. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης παραγράφου σε όλες τις παραγράφους των κελιών του πίνακα. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης τμήματος σε όλα τα τμήματα των κελιών του πίνακα. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Ορίζει τις καθορισμένες ιδιότητες μορφοποίησης πλαισίου κειμένου σε όλα τα πλαίσια κειμένου των κελιών του πίνακα. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GraphicalObject](../graphicalobject)
* διεπαφή [ITable](../itable)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->