---
title: IShape
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ένα σχήμα σε μια διαφάνεια.
type: docs
weight: 6930
url: /el/aspose.slides/ishape/
---
## IShape interface

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Properties

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Επιτρέπει την απόκτηση της βασικής IHyperlinkContainer διεπαφής. Μόνο για ανάγνωση [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Επιτρέπει την απόκτηση της βασικής ISlideComponent διεπαφής. Μόνο για ανάγνωση [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Αποκτά ή ορίζει την επιλογή «Mark as decorative». Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder. Μόνο για ανάγνωση Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στο slide που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα interop να αναφέρεται αξιόπιστα στο shape από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Επιστρέφει το γονικό GroupShape αντικείμενο εάν το σ shape είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σ shape. Μόνο για ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σ shape. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό μοιρών κατά τις οποίες το συγκεκριμένο σ shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σ shape. Μόνο για ανάγνωση [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Επιστρέφει το ThreeDFormat αντικείμενο που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σ shape. Μόνο για ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να αλλάξει από το χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Αποκτά ή ορίζει το πλάτος του σ shape, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Αποκτά ή ορίζει την x-συντεταγμένη της επάνω αριστερής γωνίας του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Αποκτά ή ορίζει την y-συντεταγμένη της επάνω αριστερής γωνίας του σ shape, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σ shape στην σειρά z. Shapes[0] επιστρέφει το σ shape στο βάθος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σ shape στο μπροστά της σειράς z. Μόνο για ανάγνωση Int32. |

## Methods

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder αν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Επιστρέφει ένα βασικό placeholder shape (σ shape από τη διάταξη και/ή το κύριο slide από το οποίο κληρονομείται το τρέχον σ shape). Επιστρέφεται null εάν το τρέχον σ shape δεν κληρονομείται. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Επιστρέφει μικρογραφία σ shape. Το είδος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ ορισμού. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σ shape. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Ορίζει ότι αυτό το σ shape δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* διασύνδεση [IHyperlinkContainer](../ihyperlinkcontainer)
* διασύνδεση [ISlideComponent](../islidecomponent)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->