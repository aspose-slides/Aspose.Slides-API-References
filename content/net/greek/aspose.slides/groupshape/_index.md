---
title: GroupShape
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια ομάδα σχημάτων σε μια διαφάνεια.
type: docs
weight: 5070
url: /el/aspose.slides/groupshape/
---
## GroupShape κλάση

Αναπαριστά μια ομάδα σχημάτων σε μια διαφάνεια.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/γραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/γραφή String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Επιτρέπει την πρόσβαση στη βάση IShape διεπαφή. Μόνο-ανάγνωση [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα εμφανίζεται ένα σχήμα σε λειτουργία ασπρόμαυρης απεικόνισης. Ανάγνωση/γραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείου που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/γραφή [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε μονάδες point. Ανάγνωση/γραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/γραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Ανάγνωση/γραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσύνδεσμου. Μόνο-ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για hover του ποντικιού. Ανάγνωση/γραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/γραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: Επιστρέφει null για αντικείμενα GroupShape επειδή δεν έχουν ιδιότητες γραμμής. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε τιμή κενής συμβολοσειράς αν χρειάζεται. Ανάγνωση/γραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα interop να αναφορά το σχήμα αξιόπιστα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το σύμβολο κράτησης θέσης (placeholder) για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης θέσης. Μόνο-ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο-ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες πλαισίου του σχήματος. Ανάγνωση/γραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/γραφή Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [`IGroupShapeLock`](../igroupshapelock). (2 ιδιότητες) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Επιστρέφει τη συλλογή των σχημάτων μέσα στην ομάδα. Μόνο-ανάγνωση [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο-ανάγνωση [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν 3D ιδιότητες. Μόνο-ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο σε παρουσίαση αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλον κώδικα. Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε μονάδες point. Ανάγνωση/γραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες point. Ανάγνωση/γραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες point. Ανάγνωση/γραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην τάξη z. Shapes[0] επιστρέφει το σχήμα στο βάθος της τάξης z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο προσκήνιο της τάξης z. Μόνο-ανάγνωση Int32. |

## Μεθόδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null αν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [Shape](../shape)
* διασύνδεση [IGroupShape](../igroupshape)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->