---
title: InkActions
second_title: Aspose.Sildes για .NET - Αναφορά API
description: Αντιπροσωπεύει τη ρίζα των ενεργειών μελάνης.
type: docs
weight: 7560
url: /el/aspose.slides.ink/inkactions/
---
## InkActions κλάση

Represents the root of ink actions.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδοθεί ένα σχήμα σε λειτουργία μαύρου-λευκού. Ανάγνωση/Εγγραφή [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρώντας σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/Εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει το διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για ποντίκι πάνω. Ανάγνωση/Εγγραφή [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/Εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Ανάγνωση/Εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό κατά τη διάρκεια της ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον διαλειτουργικό κώδικα να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το αντικείμενο GroupShape γονέα εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το σύμβολο κράτησης θέσης για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο ανάγνωση [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/Εγγραφή Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ιδιότητες) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3Δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν 3Δ ιδιότητες. Μόνο ανάγνωση [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο σε παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να ανατεθεί εκ νέου από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρώντας σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρώντας σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρώντας σε σημεία. Ανάγνωση/Εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην σειρά z. Το Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, ενώ το Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο σύμβολο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολου κράτησης σε ένα συγκεκριμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφει null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δες επίσης

* κλάση [GraphicalObject](../../aspose.slides/graphicalobject)
* διασύνδεση [IInkActions](../iinkactions)
* χώρο ονομάτων [Aspose.Slides.Ink](../../aspose.slides.ink)
* συστοιχία [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->