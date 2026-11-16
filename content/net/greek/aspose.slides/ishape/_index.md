---
title: IShape
second_title: Aspose.Sildes για .NET – Αναφορά API
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
weight: 6970
url: /el/aspose.slides/ishape/
---
## IShape διασύνδεση

Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IHyperlinkContainer. Μόνο-ανάγνωση [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής ISlideComponent. Μόνο-ανάγνωση [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/Εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Επιστρέφει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Επιστρέφει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/Εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder. Μόνο-ανάγνωση Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Ανάγνωση/Εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό scoped σε διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape αν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Μόνο-ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/Εγγραφή Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Επιστέ φει ένα εσωτερικό αναγνωριστικό scoped στην παρουσία, προοριζόμενο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Επιστρέφει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Επιστρέφει ή ορίζει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην ταξινόμηση z. Το Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της ταξινόμησης z, και το Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός μέρος της ταξινόμησης z. Μόνο-ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder αν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ ορισμού. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Ορίζεται ότι αυτό το σχήμα δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενό του Shape ως αρχείο SVG. |

### Δείτε επίσης

* διασύνδεση [IHyperlinkContainer](../ihyperlinkcontainer)
* διασύνδεση [ISlideComponent](../islidecomponent)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->