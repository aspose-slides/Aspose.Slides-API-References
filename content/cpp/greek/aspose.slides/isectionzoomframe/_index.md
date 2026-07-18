---
title: ISectionZoomFrame
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά ένα αντικείμενο Section Zoom σε μια διαφάνεια.
type: docs
weight: 3602
url: /el/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame κλάση

Αντιπροσωπεί ένα αντικείμενο [Section](../section/) Zoom σε μια διαφάνεια.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Προσθέτει ένα νέο κράτημα χώρου αν δεν υπάρχει και ορίζει τις ιδιότητες του κράτηματος χώρου σε ένα καθορισμένο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα αναφοράς τύπου σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Επιστρέφει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποδίδεται σε κατάσταση ασπρόμαυρης προβολής. Διαβάστε [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο ανάγνωση [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Μόνο ανάγνωση [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο ανάγνωση [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Επιστρέφει τις ιδιότητες του πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Λαμβάνει το ύψος του σχήματος, μετρόμενο σε σημεία. Ανάγνωση **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Καθορίζει αν το σχήμα είναι κρυφό. Ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Διαχειριστής υπερσυνδέσμων Μόνο ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για πλοήγηση με ποντίκι. Διαβάστε [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Λαμβάνει τον τύπο εικόνας ενός αντικειμένου Zoom. Διαβάστε [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Λαμβάνει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο ανάγνωση **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Καθορίζει αν το σχήμα είναι TextHolder. Μόνο ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο ανάγνωση [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Επιστρέφει το όνομα ενός σχήματος. Διαβάστε [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Επιστρέφει ένα μοναδικό αναγνωριστικό εστιασμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα διαλειτουργικότητας να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο ανάγνωση [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Επιστρέφει το κράτημα χώρου για ένα σχήμα. Μόνο ανάγνωση [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο ανάγνωση [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Επιστρέφει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Λαμβάνει τη συμπεριφορά πλοήγησης στην παρουσίαση. Ανάγνωση **bool**. Προεπιλεγμένη τιμή: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Επιστρέφει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Λαμβάνει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Ανάγνωση **bool**. Προεπιλεγμένη τιμή: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο ανάγνωση [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | Λαμβάνει το αντικείμενο ενότητας στο οποίο συνδέεται το [Section](../section/) Zoom. Διαβάστε [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο ανάγνωση [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Λαμβάνει τη διάρκεια της μετάπτωσης μεταξύ Zoom και διαφάνειας. Ανάγνωση **float**. Προεπιλεγμένη τιμή: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Επιστρέφει ένα εσωτερικό, εστιασμένο στην παρουσίαση αναγνωριστικό που προορίζεται για χρήση από πρόσθετα ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναταξινομηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να αντιμετωπίζεται ως μόνιμο μοναδικό κλειδί. Μόνο ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Λαμβάνει το πλάτος του σχήματος, μετρόμενο σε σημεία. Ανάγνωση **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Λαμβάνει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του σχήματος, μετρόμενη σε σημεία. Ανάγνωση **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Λαμβάνει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του σχήματος, μετρόμενη σε σημεία. Ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Λαμβάνει εικόνα για το αντικείμενο Zoom. Διαβάστε [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Επιστρέφει ένα βασικό σχήμα κράτημα χώρου (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ορίων μικρογραφίας [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) χρησιμοποιείται εξ' ορισμού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Επιστρέφει τη μικρογραφία του σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου φύλακα [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγράφου. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την αντιγραφή δημιουργίας υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει κάτι, στην πραγματικότητα, απλώς αρχικοποιεί ένα νέο αντικείμενο και επιτρέπει την αντιγραφή δημιουργίας υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής τύπου αντικειμένου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Καθορίζει ότι αυτό το σχήμα δεν είναι κράτημα χώρου. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποδίδεται σε κατάσταση ασπρόμαυρης προβολής. Εγγραφή [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ορίζει το ύψος του σχήματος, μετρόμενο σε σημεία. Εγγραφή **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Καθορίζει αν το σχήμα είναι κρυφό. Εγγραφή **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για πλοήγηση με ποντίκι. Εγγραφή [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Ορίζει τον τύπο εικόνας ενός αντικειμένου Zoom. Εγγραφή [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ορίζει την επιλογή 'Mark as decorative'. Εγγραφή/ανάγνωση **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός σχήματος. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ορίζει τις ακατέργαστες ιδιότητες πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Εγγραφή **bool**. Προεπιλεγμένη τιμή: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Εγγραφή **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Ορίζει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Εγγραφή **bool**. Προεπιλεγμένη τιμή: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το [Section](../section/) Zoom. Εγγραφή [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Ορίζει τη διάρκεια της μετάπτωσης μεταξύ Zoom και διαφάνειας. Εγγραφή **float**. Προεπιλεγμένη τιμή: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ορίζει το πλάτος του σχήματος, μετρόμενο σε σημεία. Εγγραφή **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ορίζει τη συντεταγμένη x του άνω αριστερού γωνιακού σημείου του σχήματος, μετρόμενη σε σημεία. Εγγραφή **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ορίζει τη συντεταγμένη y του άνω αριστερού γωνιακού σημείου του σχήματος, μετρόμενη σε σημεία. Εγγραφή **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Ορίζει εικόνα για το αντικείμενο Zoom. Εγγραφή [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμε pointer (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του statement lock() της C#. Κλήση άμεσα ή χρήση του αντικειμένου φύλακα [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IZoomObject](../izoomobject/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)