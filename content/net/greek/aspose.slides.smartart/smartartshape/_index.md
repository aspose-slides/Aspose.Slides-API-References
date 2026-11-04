---
title: SmartArtShape
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει το σχήμα SmartArt
type: docs
weight: 10680
url: /el/aspose.slides.smartart/smartartshape/
---
## SmartArtShape κλάση

Αντιπροσωπεύει το σχήμα SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή των τιμών προσαρμογής του σχήματος. Μόνο ανάγνωση [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυμμένο. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσύνδεσμου. Μόνο ανάγνωση [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να είναι μη μηδενικό. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό ταυτοποιητή περιορισμένο σε διαφάνεια, που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφορά το σχήμα αξιόπιστα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το αντικείμενο γονικό GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο ανάγνωση [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο ανάγνωση [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο προεπιλογής γεωμετρίας. Σημείωση: με την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλεγμένες τιμές τους. Ανάγνωση/εγγραφή [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Επιστρέφει το κείμενο του σχήματος SmartArt. Μόνο ανάγνωση [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d. Μόνο ανάγνωση [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο σε παρουσίαση ταυτοποιητή που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z-order. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς, ενώ Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομεί το τρέχον σχήμα). Επιστρέφει null εάν το τρέχον σχήμα δεν κληρονομεί. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει τη μικρογραφία του σχήματος. Τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ' ορισμού. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../../aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](../../aspose.slides/igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GeometryShape](../../aspose.slides/geometryshape)
* διασύνδεση [ISmartArtShape](../ismartartshape)
* χώρο ονομάτων [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->