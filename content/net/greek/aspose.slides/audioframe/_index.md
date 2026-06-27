---
title: AudioFrame
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει ένα ηχητικό απόσπασμα σε μια διαφάνεια.
type: docs
weight: 850
url: /el/aspose.slides/audioframe/
---
## AudioFrame κλάση

Represents an audio clip on a slide.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Επιστρέφει μια συλλογή των τιμών ρυθμίσεων του σχήματος. Μόνο ανάγνωση [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Λαμβάνει ή ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Λαμβάνει ή ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Ανάγνωση/εγγραφή String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Λαμβάνει ή ορίζει το τελικό δείκτη κομματιού. Ανάγνωση/εγγραφή Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Λαμβάνει ή ορίζει τον χρόνο λήξης του κομματιού. Ανάγνωση/εγγραφή Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Λαμβάνει ή ορίζει το δείκτη έναρξης κομματιού. Ανάγνωση/εγγραφή Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Λαμβάνει ή ορίζει τον χρόνο έναρξης του κομματιού. Ανάγνωση/εγγραφή Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Ιδιότητα που καθορίζει πώς θα αποδίδεται ένα σχήμα σε κατάσταση ασπρομαύρης προβολής. Ανάγνωση/εγγραφή [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [`ICaptionsCollection`](../icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Επιστρέφει το αντικείμενο EffectFormat που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχήματος που δεν έχουν ιδιότητες εφέ. Μόνο ανάγνωση [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Καθορίζει εάν ήχος είναι ενσωματωμένος στην παρουσίαση. Μόνο ανάγνωση Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Λαμβάνει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/εγγραφή [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Καθορίζει τη διάρκεια του αρχικού fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Καθορίζει τη διάρκεια του τελικού fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Επιστρέφει το αντικείμενο FillFormat που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχήματος που δεν έχουν ιδιότητες γεμίσματος. Μόνο ανάγνωση [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Λαμβάνει ή ορίζει τις ιδιότητες του πλαισίου σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Λαμβάνει ή ορίζει το ύψος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Καθορίζει εάν το σχήμα είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Καθορίζει εάν το AudioFrame είναι κρυφό. Ανάγνωση/εγγραφή Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Λαμβάνει ή ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Επιστρέφει το διαχειριστή υπερσύνδεσης. Μόνο ανάγνωση [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Λαμβάνει ή ορίζει τον υπερσύνδεσμο που ορίζεται για τοπική κίνηση ποντικιού. Ανάγνωση/εγγραφή [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Καθορίζει εάν το PictureFrame είναι αντικείμενο Cameo ή όχι. Μόνο ανάγνωση Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Λαμβάνει ή ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο ανάγνωση Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Επιστρέφει το αντικείμενο LineFormat που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχήματος που δεν έχουν ιδιότητες γραμμής. Μόνο ανάγνωση [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Λαμβάνει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. Ανάγνωση/εγγραφή String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Λαμβάνει ή ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Ανάγνωση/εγγραφή String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο σε διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφερθεί αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση UInt32. Δείτε επίσης [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Επιστρέφει το γονικό αντικείμενο GroupShape εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Επιστρέφει το αντικείμενο PictureFillFormat για ένα πλαίσιο εικόνας. Μόνο ανάγνωση [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο ανάγνωση [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Καθορίζει εάν ο ήχος αναπαράγεται σε όλες τις διαφάνειες. Ανάγνωση/εγγραφή Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Καθορίζει εάν ο ήχος επαναλαμβάνεται. Ανάγνωση/εγγραφή Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Λαμβάνει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/εγγραφή [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο ανάγνωση [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Λαμβάνει ή ορίζει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Ανάγνωση/εγγραφή [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Λαμβάνει ή ορίζει την κλίμακα του ύψους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Λαμβάνει ή ορίζει την κλίμακα του πλάτους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση/εγγραφή Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Καθορίζει εάν ο ήχος επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/εγγραφή Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μία θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση/εγγραφή Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [`IPictureFrameLock`](../ipictureframelock). (2 ιδιότητες) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο ανάγνωση [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Λαμβάνει ή ορίζει τον τύπο AutoShape για ένα PictureFrame. Επιτρέπονται όλα τα στοιχεία του συνόλου [`ShapeType`](../shapetype), εκτός όλων των τύπων γραμμών: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο ανάγνωση [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Επιστρέφει το αντικείμενο ThreeDFormat που περιέχει τις ιδιότητες 3D εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχήματος που δεν έχουν ιδιότητες 3D. Μόνο ανάγνωση [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Καθορίζει τη διάρκεια του χρόνου που πρέπει να αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Καθορίζει τη διάρκεια του χρόνου που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Επιστρέφει ένα εσωτερικό, περιορισμένο σε παρουσίαση αναγνωριστικό προοριζόμενο για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να ανατεθεί ξανά από το χρήστη ή προγραμματικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση UInt32. Δείτε επίσης [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Λαμβάνει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Λαμβάνει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/εγγραφή Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του σχήματος, μετρημένο σε points. Ανάγνωση/εγγραφή Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη x του επάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Λαμβάνει ή ορίζει τη συντεταγμένη y του επάνω αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε points. Ανάγνωση/εγγραφή Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο ανάγνωση Int32. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια master από την οποία κληρονομείται το τρέχον σχήμα). Επιστρέφεται null εάν το τρέχον σχήμα δεν κληρονομείται. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του σχήματος. |
| [GetImage](../../aspose.slides/shape/getimage)() | Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ShapeThumbnailBounds.Shape χρησιμοποιείται εξ ορισμού. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Επιστρέφει τη μικρογραφία του σχήματος. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Λαμβάνει τα οπτικά όρια του σχήματος, υπολογισμένα από το αποδοθέν περιεχόμενό του. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Ενημερώνει τη γεωμετρία του σχήματος από έναν πίνακα [`IGeometryPath`](../igeometrypath). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([`ShapeType`](../geometryshape/shapetype)) σε Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Αποθηκεύει το περιεχόμενο του Shape ως αρχείο SVG. |

### Παραδείγματα

Τα παρακάτω παραδείγματα δείχνουν πώς να αλλάξετε τις επιλογές αναπαραγωγής ήχου.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Λαμβάνει το σχήμα AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Ορίζει τη λειτουργία αναπαραγωγής σε αναπαραγωγή με κλικ
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Ορίζει την ένταση σε Χαμηλή
    audioFrame.Volume = AudioVolumeMode.Low;
    // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
    audioFrame.PlayAcrossSlides = true;
    // Απενεργοποιεί την επανάληψη του ήχου
    audioFrame.PlayLoopMode = false;
    // Κρύβει το AudioFrame κατά τη διάρκεια της παρουσίασης
    audioFrame.HideAtShowing = true;
    // Επαναφέρει τον ήχο στην αρχή μετά την αναπαραγωγή
    audioFrame.RewindAudio = true;
    // Αποθηκεύει το αρχείο PowerPoint στον δίσκο
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* κλάση [PictureFrame](../pictureframe)
* διασύνδεση [IAudioFrame](../iaudioframe)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->