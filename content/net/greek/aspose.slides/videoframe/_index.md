---
title: VideoFrame
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά ένα βίντεο σε μια διαφάνεια.
type: docs
weight: 11740
url: /el/aspose.slides/videoframe/
---
## VideoFrame κλάση

Αναπαριστά ένα βίντεο σε μια διαφάνεια.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή από τιμές προσαρμογής του σχήματος. Μόνο ανάγνωση [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Επιστρέφει ή ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Επιστρέφει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Ανάγνωση/Εγγραφή String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Ανάγνωση/Εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Αποκτά τη συλλογή των κλειστών λεζαντών που σχετίζονται με το πλαίσιο βίντεο. Αυτή η ιδιότητα είναι μόνο ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](../icaptionscollection) που περιέχει όλα τα κομμάτια λεζαντών. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης του σχήματος. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/Εγγραφή [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Επιστρέφει ή ορίζει τις ιδιότητες του πλαισίου του σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Καθορίζει αν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθνης. Ανάγνωση/Εγγραφή Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Αποκτά ή ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Καθορίζει αν ένα VideoFrame είναι κρυφό. Ανάγνωση/Εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/Εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Επιστρέφει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοποθέτηση ποντικιού. Ανάγνωση/Εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Καθορίζει αν το PictureFrame είναι αντικείμενο Cameo ή όχι. Μόνο ανάγνωση Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Αποκτά ή ορίζει την επιλογή 'Σήμανση ως διακοσμητικό'. Ανάγνωση/Εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει αν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. Ανάγνωση/Εγγραφή String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Επιστρέφει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειαστεί. Ανάγνωση/Εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape αν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. Μόνο ανάγνωση [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Επιστρέφει τα κλειδώς του σχήματος. Μόνο ανάγνωση [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null αν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Καθορίζει αν ένα βίντεο επαναλαμβάνεται. Ανάγνωση/Εγγραφή Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Επιστρέφει ή ορίζει την κατάσταση αναπαραγωγής βίντεο. Ανάγνωση/Εγγραφή [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Επιστρέφει ή ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Ανάγνωση/Εγγραφή [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Επιστρέφει ή ορίζει την κλίμακα του ύψους (σχετικό με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/Εγγραφή Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Επιστρέφει ή ορίζει την κλίμακα του πλάτους (σχετικό με το αρχικό μέγεθος εικόνας) του πλαισίου εικόνας. Τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/Εγγραφή Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Καθορίζει αν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η προβολή. Ανάγνωση/Εγγραφή Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Επιστρέφει ή ορίζει τον αριθμό των μοιρών με την οποία το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη. Ανάγνωση/Εγγραφή Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Επιστρέφει τα κλειδός του σχήματος. Μόνο ανάγνωση [`IPictureFrameLock`](../ipictureframelock). (2 ιδιότητες) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο ανάγνωση [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Επιστρέφει ή ορίζει τον τύπο AutoShape για ένα PictureFrame. Υπάρχουν όλα τα επιτρεπτά στοιχεία του συνόλου [`ShapeType`](../shapetype), εκτός όλων των τύπων γραμμών: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3δ. Μόνο ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Περικοπή τέλους [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Περικοπή αρχής [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, εντός παρουσίασης αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναληφθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Επιστρέφει ή ορίζει την ένταση ήχου. Ανάγνωση/Εγγραφή [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. Η τιμή εκφράζεται ως ποσοστό από 0 έως 100. Χρησιμοποιήστε αυτήν την ιδιότητα για ανάγνωση ή ρύθμιση τιμών έντασης που είναι πιο ακριβείς από τα προ-ορισμένα επίπεδα διαθέσιμα μέσω της ιδιότητας [`Volume`](./volume). Ανάγνωση/Εγγραφή Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Αποκτά ή ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη x της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Αποκτά ή ορίζει τη συντεταγμένη y της επάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Ανάγνωση/Εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στην σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα μπροστά. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα από τα στοιχεία του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια-μαστέρ από την οποία κληρονομείται το τρέχον σχήμα). Επιστρέφεται null αν το τρέχον σχήμα δεν κληρονομείται. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την πάνω αριστερή γωνία του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ' ορισμού. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει μικρογραφία σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομημένο περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικά με την πάνω αριστερή γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικά με την πάνω αριστερή γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Δείτε επίσης

* κλάση [PictureFrame](../pictureframe)
* διασύνδεση [IVideoFrame](../ivideoframe)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->