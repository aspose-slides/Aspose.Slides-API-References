---
title: AutoShape
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ένα AutoShape.
type: docs
weight: 880
url: /el/aspose.slides/autoshape/
---
## AutoShape κλάση

Αντιπροσωπεύει ένα AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή τιμών προσαρμογής του σχήματος. Μόνο για ανάγνωση [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Επιστρέφει τα κλειδαριά του autoshape. Μόνο για ανάγνωση [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία απλοϊκής (μαυρό-ασπρό) προβολής. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος του σχήματος, μετρημένο σε μονάδες σημείου. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοποθέτηση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Επιστρέφει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό' Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Καθορίζει αν το σχήμα είναι πλαίσιο κειμένου. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο για ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διαλειτουργικότητας να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το σύμβολο κράτησης (placeholder) για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο για ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Επιστρέφει τα κλειδαριά του σχήματος. Μόνο για ανάγνωση [`IAutoShapeLock`](../iautoshapelock). (2 ιδιότητες) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο για ανάγνωση [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. Σημείωση: με την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλογές τους. Ανάγνωση/εγγραφή [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Επιστρέφει το αντικείμενο TextFrame για το AutoShape. Μόνο για ανάγνωση [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ. Μόνο για ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, εντός παρουσίασης αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Επειδή αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Καθορίζει αν αυτό το autoshape πρέπει να γεμιστεί με το γέμισμα φόντου της διαφάνειας αντί για το καθορισμένο από το στυλ ή το FillFormat. Ανάγνωση/εγγραφή Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος του σχήματος, μετρημένο σε μονάδες σημείου. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες σημείου. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε μονάδες σημείου. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην ταξινόμηση z. Shapes[0] επιστρέφει το σχήμα στο βάθος της ταξινόμησης z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός της ταξινόμησης z. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Προσθέτει ένα νέο TextFrame σε ένα σχήμα. Εάν το σχήμα έχει ήδη TextFrame τότε απλώς αλλάζει το κείμενό του. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη βασική διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφει null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει ένα αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την πάνω αριστερή γωνία του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται προεπιλογή για τα όρια μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Επιστρέφει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την πάνω αριστερή γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την πάνω αριστερή γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GeometryShape](../geometryshape)
* διεπαφή [IAutoShape](../iautoshape)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->