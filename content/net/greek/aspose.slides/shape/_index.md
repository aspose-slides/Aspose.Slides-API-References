---
title: Shape
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
weight: 9850
url: /el/aspose.slides/shape/
---
## Shape κλάση

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.

```csharp
public class Shape : IShape
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο-ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοποθέτηση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε την κενή συμβολοσειρά εάν απαιτείται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει έναν μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια, ο οποίος παραμένει σταθερός κατά τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το αντικείμενο γονέα GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο-ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την κύρια παρουσίαση μιας διαφάνειας. Μόνο-ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο-ανάγνωση [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο-ανάγνωση [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d. Μόνο-ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναπραγματοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται ως μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο-ανάγνωση Int32. |

## Μεθόδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Επιστρέφει την μικρογραφία του σχήματος. Το ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τον τύπο ορίων μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Επιστρέφει την μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενο. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι το σχήμα δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISSVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* διεπαφή [IShape](../ishape)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->