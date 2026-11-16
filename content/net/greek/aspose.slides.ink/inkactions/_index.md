---
title: InkActions
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει τη ρίζα των ενεργειών μελάνης.
type: docs
weight: 7580
url: /el/aspose.slides.ink/inkactions/
---
## InkActions κλάση

Αντιπροσωπεύει τη ρίζα των ενεργειών μελάνης.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποτυπωθεί ένα σχήμα σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σ_shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε μονάδες. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Προσδιορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πλάγιση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Προσδιορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Προσδιορίζει εάν το σ_shape είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σ_shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σ_shape. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή τιμή συμβολοσειράς εάν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στην διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σ_shape και επιτρέπει στο PowerPoint ή στον κώδικα interop να το αναφέρει αξιόπιστα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σ_shape είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σ_shape. Επιστρέφει null εάν το σ_shape δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την κύρια παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σ_shape. Ανάγνωση/εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το σ_shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σ_shape. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ιδιότητες) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη μητρική διαφάνεια ενός σ_shape. Μόνο ανάγνωση [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σ_shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες 3D. Μόνο ανάγνωση [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σ_shape, μετρημένο σε μονάδες. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει την x-συντεταγμένη της άνω-αριστερής γωνίας του σ_shape, μετρημένη σε μονάδες. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει την y-συντεταγμένη της άνω-αριστερής γωνίας του σ_shape, μετρημένη σε μονάδες. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σ_shape στη σειρά z. Shapes[0] επιστρέφει το σ_shape στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σ_shape στο μπροστινό μέρος της σειράς z. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σ shape placeholder (σ shape από τη διάταξη και/ή τη διαφάνεια master από την οποία κληρονομείται το τρέχον σ shape). Επιστρέφεται null εάν το τρέχον σ shape δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει τη μικρογραφία του σ shape. Η προεπιλεγμένη χρησιμοποιείται η μορφή ShapeThumbnailBounds.Shape για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει τη μικρογραφία του σ shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σ shape που υπολογίζονται από το αποδιδόμενο περιεχόμενο. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σ shape δεν είναι placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [GraphicalObject](../../aspose.slides/graphicalobject)
* διεπαφή [IInkActions](../iinkactions)
* χώρος ονομάτων [Aspose.Slides.Ink](../../aspose.slides.ink)
* σύστημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->