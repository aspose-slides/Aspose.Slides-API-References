---
title: OleObjectFrame
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
weight: 9210
url: /el/aspose.slides/oleobjectframe/
---
## OleObjectFrame κλάση

Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Επιτρέπει την απόκτηση της βασικής διεπαφής IGraphicalObject. Μόνο-ανάγνωση [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποτυπώνεται σε λειτουργία ασπρόμαυρης προβολής. Ανάγνωση/Εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο-ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Αποκτά ή ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Ανάγνωση/Εγγραφή [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε πόντους. Ανάγνωση/Εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/Εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει το διαχειριστή υπερσυνδέσμου. Μόνο-ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοποθέτηση ποντικιού. Ανάγνωση/Εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Αποκτά ή ορίζει την επιλογή ‘Σημείωση ως διακοσμητικό’. Ανάγνωση/Εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση/Εγγραφή Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο-ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο-ανάγνωση [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Επιστρέφει τη πλήρη διαδρομή προς ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο-ανάγνωση String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Επιστρέφει τη πλήρη διαδρομή προς ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Ανάγνωση/Εγγραφή String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Επιστρέφει τη σχετική διαδρομή προς ένα συνδεδεμένο αρχείο αν υπάρχει, διαφορετικά επιστρέφει κενό string. Μόνο-ανάγνωση String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Δεν πρέπει να είναι null. Χρησιμοποιήστε κενή τιμή string εάν χρειάζεται. Ανάγνωση/Εγγραφή String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός αντικειμένου. Ανάγνωση/Εγγραφή String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο-ανάγνωση String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια, το οποίο παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null αν το σχήμα δεν έχει placeholder. Μόνο-ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο-ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τους οποίους το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/Εγγραφή Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 ιδιότητες) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο-ανάγνωση [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο-ανάγνωση [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο για το εικονίδιο OleObject. Ανάγνωση/Εγγραφή String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d. Μόνο-ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση/Εγγραφή Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε πόντους. Ανάγνωση/Εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη x της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Ανάγνωση/Εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη y της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Ανάγνωση/Εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο-ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια της μικρογραφίας. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Αποκτά τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Αυτή η μέθοδος τροποποιεί τις ιδιότητες του αντικειμένου ώστε να αντανακλούν τα νέα δεδομένα και θέτει τη σημαία IsObjectLink σε false, υποδεικνύοντας ότι το αντικείμενο OLE είναι ενσωματωμένο. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να αποκτήσετε πρόσβαση σε πλαίσια OLE Object.

```csharp
[C#]
// Φορτώνει το PPTX σε ένα αντικείμενο παρουσίασης
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Πρόσβαση στην πρώτη διαφάνεια
    ISlide sld = pres.Slides[0];
    // Κάνει cast το σχήμα σε OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Διαβάζει το αντικείμενο OLE και το γράφει στο δίσκο
    if (oleObjectFrame != null)
    {
        // Λαμβάνει τα δεδομένα ενσωματωμένου αρχείου
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Λαμβάνει την επέκταση ενσωματωμένου αρχείου
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Δημιουργεί διαδρομή για την αποθήκευση του εξαγόμενου αρχείου
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
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->