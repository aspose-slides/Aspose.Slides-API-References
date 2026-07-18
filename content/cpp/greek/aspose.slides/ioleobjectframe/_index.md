---
title: IOleObjectFrame
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
weight: 3095
url: /el/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame κλάση


Represents an OLE object on a slide.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Προσθέτει μια νέα δεσμευμένη θέση εάν δεν υπάρχει και ορίζει τις ιδιότητες της δεσμευμένης θέσης σε μια καθορισμένη. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς στο στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής στο στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Επιστρέφει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποτυπώνεται σε ασπρόμαυρη λειτουργία εμφάνισης. Διαβάστε [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε σχήμα. Μόνο-ανάγνωση [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | Λαμβάνει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Μόνο-ανάγνωση [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο-ανάγνωση [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Επιστρέφει τις ιδιότητες του πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Επιστρέφει τις κλειδαριές του σχήματος. Μόνο-ανάγνωση [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Λαμβάνει το ύψος του σχήματος, μετρημένο σε σημεία. Διαβάστε **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Καθορίζει εάν το σχήμα είναι κρυμμένο. Διαβάστε **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Επιστρέφει τη σύνδεση (hyperlink) που ορίζεται για κλικ ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Διαχειριστής συνδέσμων (hyperlinks). Μόνο-ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Επιστρέφει τη σύνδεση που ορίζεται για υπέρπλοτ ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Λαμβάνει την επιλογή 'Σημείο ως διακοσμητικό'. Ανάγνωση/εγγραφή **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Διαβάστε **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο-ανάγνωση **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Καθορίζει εάν το σχήμα είναι TextHolder. Μόνο-ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | Επιστρέφει την πλήρης διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το σύντομο όνομα αρχείου. Μόνο-ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Επιστρέφει την πλήρης διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει, αλλιώς επιστρέφει κενή συμβολοσειρά. Μόνο-ανάγνωση [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Επιστρέφει το όνομα ενός σχήματος. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | Επιστρέφει το όνομα ενός αντικειμένου. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο-ανάγνωση [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Επιστρέφει ένα μοναδικό αναγνωριστικό εντός διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Επιστρέφει το δεσμευτικό στοιχείο (placeholder) για ένα σχήμα. Μόνο-ανάγνωση [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο-ανάγνωση [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Επιστρέφει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Επιστρέφει τον αριθμό των μοιρών με τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη. Διαβάστε **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Επιστρέφει τις κλειδαριές του σχήματος. Μόνο-ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο-ανάγνωση [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο-ανάγνωση [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | Επιστρέφει τον τίτλο για το εικονίδιο OleObject. Διαβάστε [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο-ανάγνωση [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, ταυτοποιητή που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να ανατεθεί εκ νέου από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Διαβάστε **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Λαμβάνει το πλάτος του σχήματος, μετρημένο σε σημεία. Διαβάστε **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Λαμβάνει την x-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Διαβάστε **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Λαμβάνει την y-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Διαβάστε **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Επιστρέφει τη θέση ενός σχήματος στην κατάταξη z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της κατάταξης z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο εμπρός μέρος της κατάταξης z. Μόνο-ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή τη κύρια διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Επιστρέφει μικρογραφία σχήματος. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) τύπος ορίων μικρογραφίας χρησιμοποιείται εξ'ορισμού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Επιστρέφει μικρογραφία σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσθέτης ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την ορισμένη τιμή. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Ορίζει ότι αυτό το σχήμα δεν είναι δεσμευτικό στοιχείο. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποτυπώνεται σε ασπρόμαυρη λειτουργία εμφάνισης. Εγγραφή [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Εγγραφή **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Καθορίζει εάν το σχήμα είναι κρυμμένο. Εγγραφή **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τη σύνδεση που ορίζεται για κλικ ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τη σύνδεση που ορίζεται για υπέρπλοτ ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ορίζει την επιλογή 'Σημείο ως διακοσμητικό'. Ανάγνωση/εγγραφή **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Εγγραφή **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Επιστρέφει την πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί το μακρύ όνομα αρχείου. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός σχήματος. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός αντικειμένου. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο-ανάγνωση [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ορίζει τον αριθμό των μοιρών με τις οποίες το καθορισμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· αρνητική τιμή αριστερόστροφη. Εγγραφή **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | Ορίζει τον τίτλο για το εικονίδιο OleObject. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Εγγραφή **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Εγγραφή **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ορίζει την x-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Εγγραφή **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ορίζει την y-συντεταγμένη της πάνω-αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Εγγραφή **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τον κατασκευαστή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδίαση του statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει το αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει το αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [IGraphicalObject](../igraphicalobject/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)