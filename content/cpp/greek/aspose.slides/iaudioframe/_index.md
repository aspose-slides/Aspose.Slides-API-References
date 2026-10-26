---
title: IAudioFrame
second_title: Aspose.Slides για C++ API Αναγραφή
description: Αναπαριστά ένα ηχητικό κλιπ σε μια διαφάνεια.
type: docs
weight: 1353
url: /el/aspose.slides/iaudioframe/
---
## IAudioFrame κλάση

Αντιπροσωπεύει ένα ηχητικό κλιπ σε μια διαφάνεια.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα καθορισμένο. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του σχήματος. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση αριθμών κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν ισούται με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Επιστρέφει την τιμή προσαρμογών του σχήματος στον καθορισμένο δείκτη. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Επιστρέφει μια συλλογή τιμών προσαρμογών του σχήματος. Μόνο-ανάγνωση [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Επιστρέφει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Ανάγνωση [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Επιστρέφει τον τελευταίο δείκτη κομματιού. Ανάγνωση **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Επιστρέφει τον χρόνο του τελευταίου κομματιού. Ανάγνωση **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Επιστρέφει τον δείκτη του αρχικού κομματιού. Ανάγνωση **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Επιστρέφει το χρόνο του αρχικού κομματιού. Ανάγνωση **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε κατάσταση ασπρόμαυρης προβολής. Ανάγνωση [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Αποκτά τη συλλογή των κλειστών λεζαντών που συνδέονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο-ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../icaptionscollection/) που περιέχει όλα τα κομμάτια λεζάντας. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Μόνο-ανάγνωση [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Καθορίζει εάν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση. Μόνο-ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Επιστρέφει το ενσωματωμένο αντικείμενο ήχου. Ανάγνωση [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Καθορίζει τη διάρκεια χρόνου για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Καθορίζει τη διάρκεια χρόνου για την τελική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο-ανάγνωση [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Επιστρέφει τις ιδιότητες του πλαισίου σχήματος. Ανάγνωση [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Αποκτά το ύψος του σχήματος, μετρημένο σε points. Ανάγνωση **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Καθορίζει εάν το σχήμα είναι κρυμμένο. Ανάγνωση **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Καθορίζει εάν ένα [AudioFrame](../audioframe/) είναι κρυμμένο. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Ανάγνωση [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Διαχειριστής υπερσυνδέσμων. Μόνο-ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για ποντίκι πάνω. Ανάγνωση [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Αποκτά την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Καθορίζει εάν το σχήμα είναι TextHolder. Μόνο-ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Επιστρέφει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα [AudioFrame](../audioframe/). Ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Επιστρέφει το όνομα ενός σχήματος. Ανάγνωση [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Επιστρέφει έναν μοναδικό ταυτοποιητή scoped σε διαφάνεια που παραμένει σταθερός για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφερθεί αξιόπιστα στο σχήμα από οποιοδήποτε σημείο του εγγράφου. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Επιστρέφει το αντικείμενο [PictureFillFormat](../picturefillformat/) για ένα πλαίσιο εικόνας. Μόνο-ανάγνωση [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Επιστρέφει τα κλειδώματα του [PictureFrame](../pictureframe/). Μόνο-ανάγνωση [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Επιστρέφει το placeholder για ένα σχήμα. Μόνο-ανάγνωση [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Καθορίζει εάν ένας ήχος παίζει διασώρευτα στις διαφάνειες. Ανάγνωση **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Καθορίζει εάν ένας ήχος είναι σε βρόχο. Ανάγνωση **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Επιστρέφει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο-ανάγνωση [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Ανάγνωση [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Επιστρέφει την κλίμακα του ύψους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Επιστρέφει την κλίμακα του πλάτους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Καθορίζει εάν ένας ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Επιστρέφει τον αριθμό των μοιρών που το καθορισμένο σχήμα είναι περιστραμμένο γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει κυκλική περιστροφή, μια αρνητική τιμή αντιστροφή. Ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο-ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Επιστρέφει το αντικείμενο στυλ του σχήματος. Μόνο-ανάγνωση [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Επιστρέφει τον τύπο προκαθορισμένης γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλεγμένες τιμές. Ανάγνωση [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο-ανάγνωση [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Επιστρέφει έναν εσωτερικό, presentation-scoped ταυτοποιητή προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από το χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Επιστρέφει την ένταση ήχου. Ανάγνωση [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Επιστρέφει την ένταση ήχου σε ποσοστά. Ανάγνωση **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Αποκτά το πλάτος του σχήματος, μετρημένο σε points. Ανάγνωση **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Αποκτά τη συντεταγμένη x της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Αποκτά τη συντεταγμένη y της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. Ανάγνωση **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Επιστρέφει τη θέση ενός σχήματος στην σειρά z. Το Shapes[0] επιστρέφει το σχήμα στο παρασκήνιο της σειράς z, και το Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός της σειράς z. Μόνο-ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού σχήματος. Οι συντεταγμένες είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος συνόρων μικρογραφίας [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) χρησιμοποιείται εξ' ορισμού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Επιστρέφει μικρογραφία σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τον μηχανισμό κλειδώματος της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο προφύλαξης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγράφου. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή στην κατασκευή υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή στην κατασκευή υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Ορίζει έναν τελευταίο δείκτη κομματιού. Εγγραφή **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Ορίζει χρόνο τελευταίου κομματιού. Εγγραφή **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Ορίζει έναν δείκτη αρχικού κομματιού. Εγγραφή **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Ορίζει χρόνο αρχικού κομματιού. Εγγραφή **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε κατάσταση ασπρόμαυρης προβολής. Εγγραφή [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Ορίζει το ενσωματωμένο αντικείμενο ήχου. Εγγραφή [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Καθορίζει τη διάρκεια χρόνου για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Εγγραφή **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Καθορίζει τη διάρκεια χρόνου για την τελική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Εγγραφή **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ορίζει το ύψος του σχήματος, μετρημένο σε points. Εγγραφή **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Καθορίζει εάν το σχήμα είναι κρυμμένο. Εγγραφή **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Καθορίζει εάν ένα [AudioFrame](../audioframe/) είναι κρυμμένο. Εγγραφή **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για ποντίκι πάνω. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ορίζει την επιλογή 'Mark as decorative'. Εγγραφή/ανάγνωση **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα [AudioFrame](../audioframe/). Εγγραφή [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός σχήματος. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Καθορίζει εάν ένας ήχος παίζει διασώρευτα στις διαφάνειες. Εγγραφή **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Καθορίζει εάν ένας ήχος είναι σε βρόχο. Εγγραφή **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Ορίζει τη λειτουργία αναπαραγωγής ήχου. Εγγραφή [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Ορίζει την κλίμακα του ύψους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Εγγραφή **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Ορίζει την κλίμακα του πλάτους (σε σχέση με το αρχικό μέγεθος της εικόνας) του πλαισίου εικόνας. Η τιμή 1.0 αντιστοιχεί στο 100%. Εγγραφή **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Καθορίζει εάν ένας ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Εγγραφή **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ορίζει τον αριθμό των μοιρών που το καθορισμένο σχήμα είναι περιστραμμένο γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει κυκλική περιστροφή, μια αρνητική τιμή αντιστροφή. Εγγραφή **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Ορίζει τον τύπο προκαθορισμένης γεωμετρίας. Σημείωση: κατά την αλλαγή της τιμής όλες οι τιμές προσαρμογής θα επανέλθουν στις προεπιλεγμένες. Εγγραφή [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Εγγραφή **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Εγγραφή **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Ορίζει την ένταση ήχου. Εγγραφή [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Ορίζει την ένταση ήχου σε ποσοστά. Εγγραφή **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ορίζει το πλάτος του σχήματος, μετρημένο σε points. Εγγραφή **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ορίζει τη συντεταγμένη x της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. Εγγραφή **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ορίζει τη συντεταγμένη y της επάνω-αριστερής γωνίας του σχήματος, μετρημένη σε points. Εγγραφή **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Ενημερώνει τη γεωμετρία του σχήματος από το αντικείμενο [IGeometryPath](../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([ShapeType](../shapetype/)) σε [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Ενημερώνει τη γεωμετρία του σχήματος από πίνακα [IGeometryPath](../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή πάνω γωνία του σχήματος. Αλλάζει τον τύπο του σχήματος ([ShapeType](../shapetype/)) σε [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο προφύλαξης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IPictureFrame](../ipictureframe/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)