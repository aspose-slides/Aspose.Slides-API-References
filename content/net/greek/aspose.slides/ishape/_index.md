---
title: IShape
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ένα σχήμα σε μια διαφάνεια.
type: docs
weight: 6950
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
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Επιτρέπει τη λήψη της βασικής διεπαφής IHyperlinkContainer. Μόνο για ανάγνωση [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Επιτρέπει τη λήψη της βασικής διεπαφής ISlideComponent. Μόνο για ανάγνωση [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/Εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει τις εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points. Ανάγνωση/Εγγραφή Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/Εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder. Μόνο για ανάγνωση Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Ανάγνωση/Εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στο διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Επιστρέφει το αντικείμενο γονικού GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Επιστρέφει τον placeholder για ένα σχήμα. Μόνο για ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/Εγγραφή Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Επιστρέφει τα κλειδώματα του σ_shape. Μόνο για ανάγνωση [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο για ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσία αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points. Ανάγνωση/Εγγραφή Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Λαμβάνει ή ορίζει την x-συντεταγμένη της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση/Εγγραφή Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Λαμβάνει ή ορίζει την y-συντεταγμένη της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση/Εγγραφή Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σ_shape στη σειρά z. Shapes[0] επιστρέφει το σ_shape στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σ_shape στο μπροστινό μέρος της σειράς z. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Προσθέτει νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σ_shape placeholder (σ_shape από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σ_shape). Επιστρέφεται null εάν το τρέχον σ_shape δεν κληρονομείται. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Επιστρέφει μικρογραφία σ_shape. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σ_shape. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Καθορίζει ότι αυτό το σ_shape δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* διασύνδεση [IHyperlinkContainer](../ihyperlinkcontainer)
* διασύνδεση [ISlideComponent](../islidecomponent)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->