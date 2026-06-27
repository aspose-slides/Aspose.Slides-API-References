---
title: VideoFrame
second_title: Aspose.Sildes για .NET αναφορά API
description: Αντιπροσωπεύει ένα κομμάτι βίντεο σε μια διαφάνεια.
type: docs
weight: 11700
url: /el/aspose.slides/videoframe/
---
## VideoFrame κλάση

Αντιπροσωπεύει ένα βίντεο σε μια διαφάνεια.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή των τιμών ρύθμισης του σχήματος. Μόνο για ανάγνωση [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε κατάσταση εμφάνισης ασπρόμαυρης προβολής.. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο βίντεο. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](../icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/εγγραφή [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Καθορίζει εάν ένα βίντεο εμφανίζεται σε πλήρης οθόνη. Ανάγνωση/εγγραφή Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Καθορίζει εάν ένα VideoFrame είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τη hyperlink που ορίζεται για κλικ του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο για ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τη hyperlink που ορίζεται για πέρασμα του ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι. Μόνο για ανάγνωση Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Σημάδεψε ως διακοσμητικό'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο για ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. Ανάγνωση/εγγραφή String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οποιοδήποτε σημείο του εγγράφου. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. Μόνο για ανάγνωση [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο για ανάγνωση [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο για ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Καθορίζει εάν ένα βίντεο επαναλαμβάνεται. Ανάγνωση/εγγραφή Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Ανάγνωση/εγγραφή [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1,0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικά με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1,0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Καθορίζει εάν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις το αρχείο ολοκληρώσει την αναπαραγωγή. Ανάγνωση/εγγραφή Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών κατά τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο για ανάγνωση [`IPictureFrameLock`](../ipictureframelock). (2 ιδιότητες) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο για ανάγνωση [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame. Επιτρέπονται όλα τα στοιχεία του συνόλου [`ShapeType`](../shapetype), εκτός όλων των τύπων γραμμών: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ. Μόνο για ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Περικοπή τέλους [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Περικοπή έναρξης [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Επιστρέφει ή ορίζει τη ένταση ήχου. Ανάγνωση/εγγραφή [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x του επάνω αριστερού γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y του επάνω αριστερού γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στο z-order. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος του z-order, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος του z-order. Μόνο για ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια κύριου σχεδίου από το οποίο κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει το αντίγραφο του μονοπατιού του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με το αριστερό άνω άκρο του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει το μικρογραφικό του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται ως προεπιλογή για τα όρια του μικρογραφικού. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει το μικρογραφικό του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό άνω άκρο του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με το αριστερό άνω άκρο του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [PictureFrame](../pictureframe)
* διεπαφή [IVideoFrame](../ivideoframe)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->