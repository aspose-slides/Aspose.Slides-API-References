---
title: Connector
second_title: Αναφορά API Aspose.Sildes για .NET
description: Αντιπροσωπεύει έναν σύνδεσμο.
type: docs
weight: 2650
url: /el/aspose.slides/connector/
---
## Connector κλάση

Αντιπροσωπεύει ένα σύνδεσμο.

```csharp
public class Connector : GeometryShape, IConnector
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή τιμών ρυθμίσεων του σχήματος. Μόνο για ανάγνωση [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Ανάγνωση/γραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Ανάγνωση/γραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία εμφάνισης ασπρόμαυρης. Ανάγνωση/γραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Επιστρέφει τις κλειδώσεις του συνδέσμου. Μόνο για ανάγνωση [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί το άκρο του συνδέσμου. Ανάγνωση/γραφή [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το τελικό σχήμα. Ανάγνωση/γραφή UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/γραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/γραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυμμένο. Ανάγνωση/γραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/γραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/γραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Αποκτά ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/γραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο για ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειαστεί. Ανάγνωση/γραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστέφει null. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει την placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο για ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει τη γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/γραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/γραφή Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [`IConnectorLock`](../iconnectorlock). (2 ιδιότητες) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο για ανάγνωση [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο AutoShape. Ανάγνωση/γραφή [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Επιστρέφει ή ορίζει το σχήμα στο οποίο θα προσαρτηθεί η αρχή του συνδέσμου. Ανάγνωση/γραφή [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Επιστρέφει ή ορίζει τον δείκτη του σημείου σύνδεσης για το αρχικό σχήμα. Ανάγνωση/γραφή UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d. Μόνο για ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/γραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη x του πάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/γραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη y του πάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/γραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο τέλος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει μια νέα placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες της placeholder σε μια συγκεκριμένη. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη μητρική διαφάνεια από το οποίο κληρονομεί το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει το αντίγραφο του μονοπατιού του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με το αριστερό άνω άκρο του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape των ορίων μικρογραφίας σχήματος χρησιμοποιείται ως προεπιλογή. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | Αναδρομολογεί το σύνδεσμο ώστε να ακολουθεί τη συντομότερη δυνατή διαδρομή μεταξύ των σχημάτων που συνδέει. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό άνω άκρο του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό άνω άκρο του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GeometryShape](../geometryshape)
* διεπαφή [IConnector](../iconnector)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->