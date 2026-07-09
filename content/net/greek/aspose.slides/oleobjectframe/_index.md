---
title: OleObjectFrame
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αντιπροσωπεύει ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
weight: 9230
url: /el/aspose.slides/oleobjectframe/
---
## OleObjectFrame κλάση

Αντιπροσωπεύει ένα αντικείμενο OLE σε μια διαφάνεια.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Επιτρέπει την ανάκτηση της βασικής διεπαφής IGraphicalObject. Μόνο ανάγνωση [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποτυπώνεται σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Ανακτά ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Ανάγνωση/εγγραφή [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει τις ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ανακτά ή ορίζει το ύψος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ανακτά ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/εγγραφή Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει τις ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο ανάγνωση String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/εγγραφή String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει κενό string. Μόνο ανάγνωση String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Δεν πρέπει να είναι null. Χρησιμοποιήστε κενή τιμή string αν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/εγγραφή String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο ανάγνωση String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ιδιότητες) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο ανάγνωση [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/εγγραφή String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν 3δ ιδιότητες. Μόνο ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Επειδή αυτή η τιμή μπορεί να επανεκχωρηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/εγγραφή Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ανακτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ανακτά ή ορίζει την x-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ανακτά ή ορίζει την y-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην σειρά z-order. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z-order, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z-order. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από την διάταξη και/ή τη διαφάνεια προτύπου από την οποία κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ανακτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Αυτή η μέθοδος αλλάζει τις ιδιότητες του αντικειμένου ώστε να αντικατοπτρίζουν τα νέα δεδομένα και θέτει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να αποκτήσετε πρόσβαση σε πλαίσια OLE Object.

```csharp
[C#]
// Φορτώνει το PPTX σε αντικείμενο παρουσίασης
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Πρόσβαση στην πρώτη διαφάνεια
    ISlide sld = pres.Slides[0];
    // Κάνει cast το σχήμα σε OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Διαβάζει το αντικείμενο OLE και το αποθηκεύει στο δίσκο
    if (oleObjectFrame != null)
    {
        // Λαμβάνει τα ενσωματωμένα δεδομένα του αρχείου
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Λαμβάνει την επέκταση του ενσωματωμένου αρχείου
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Δημιουργεί διαδρομή για αποθήκευση του εξαγόμενου αρχείου
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Αποθηκεύει τα εξαγόμενα δεδομένα
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Δείτε επίσης

* κλάση [GraphicalObject](../graphicalobject)
* διασύνδεση [IOleObjectFrame](../ioleobjectframe)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->