---
title: IInkActions
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει ένα αντικείμενο μελάνης σε μια διαφάνεια.
type: docs
weight: 14
url: /el/aspose.slides.ink/iinkactions/
---
## IInkActions κλάση

Αντιπροσωπεύει ένα αντικείμενο μελάνης σε μια διαφάνεια.

```cpp
class IInkActions : public virtual Aspose::Slides::IGraphicalObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Προσθέτει μια νέα θέση κράτησης αν δεν υπάρχει και ορίζει τις ιδιότητες της θέσης κράτησης σε μια συγκεκριμένη. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Επιστρέφει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε κατάσταση ασπρόμαυρης εμφάνισης. Διαβάστε [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Επιστρέφει το αντικείμενο [EffectFormat](../../aspose.slides/effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Μόνο για ανάγνωση [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Επιστρέφει το αντικείμενο [FillFormat](../../aspose.slides/fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Μόνο για ανάγνωση [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Επιστρέφει τις ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Λαμβάνει το ύψος του σχήματος, μετρημένο σε πόντους. Μόνο για ανάγνωση **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Καθορίζει αν το σχήμα είναι κρυφό. Μόνο για ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Διαβάστε [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Διαχειριστής υπερσυνδέσμων Μόνο για ανάγνωση [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για πλοήγηση του ποντικιού. Διαβάστε [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Λαμβάνει την επιλογή 'Σήμανση ως διακοσμητικό' ανάγνωση/εγγραφή **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Καθορίζει αν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Καθορίζει αν το σχήμα είναι TextHolder. Μόνο για ανάγνωση **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Επιστρέφει το αντικείμενο [LineFormat](../../aspose.slides/lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο για ανάγνωση [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Επιστρέφει το όνομα ενός σχήματος. Διαβάστε [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Επιστρέφει έναν μοναδικό αναγνωριστικό εσεισής διαφάνειας που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφέρει αξιόπιστα το σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Επιστρέφει το γονικό αντικείμενο [GroupShape](../../aspose.slides/groupshape/) αν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Επιστρέφει την θέση κράτησης για ένα σχήμα. Μόνο για ανάγνωση [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Επιστρέφει την παρουσίαση. Μόνο για ανάγνωση [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Επιστρέφει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα είναι περιστραμμένο γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Μόνο για ανάγνωση **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο για ανάγνωση [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Επιστρέφει τη βασική διαφάνεια. Μόνο για ανάγνωση [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Επιστρέφει το αντικείμενο [ThreeDFormat](../../aspose.slides/threedformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Μόνο για ανάγνωση [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Επιστρέφει έναν εσωτερικό, περιορισμό-παρουσίασης αναγνωριστικό που προορίζεται για χρήση από add-ins ή άλλο κώδικα. Επειδή αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Λαμβάνει το πλάτος του σχήματος, μετρημένο σε πόντους. Μόνο για ανάγνωση **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Λαμβάνει την x-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Μόνο για ανάγνωση **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Λαμβάνει την y-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Μόνο για ανάγνωση **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Επιστρέφει τη θέση ενός σχήματος στη σειρά z-order. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος. Μόνο για ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Επιστρέφει ένα βασικό σχήμα θέση κράτησης (σχήμα από τη διάταξη και/ή τη βασική διαφάνεια από την οποία κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ορίων μικρογραφίας [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) χρησιμοποιείται εξ ορισμού. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Επιστρέφει μικρογραφία σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# `is`. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή C# lock() για κλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγραφών υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση σειράς χαρακτήρων και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση σειρών χαρακτήρων. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Ορίζει ότι αυτό το σχήμα δεν είναι θέση κράτησης. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε κατάσταση ασπρόμαυρης εμφάνισης. Γράψτε [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ορίζει τις ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Ορίζει το ύψος του σχήματος, μετρημένο σε πόντους. Γράψτε **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Καθορίζει αν το σχήμα είναι κρυφό. Γράψτε **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικίου. Γράψτε [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Ορίζει τον υπερσύνδεσμο που ορίζεται για πλοήγηση του ποντικίου. Γράψτε [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Ορίζει την επιλογή 'Σήμανση ως διακοσμητικό' ανάγνωση/εγγραφή **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Ορίζει το όνομα ενός σχήματος. Γράψτε [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Ορίζει τον αριθμό των μοιρών κατά τις οποίες το καθορισμένο σχήμα είναι περιστραμμένο γύρω από τον άξονα z. Μία θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μία αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Γράψτε **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Ορίζει το πλάτος του σχήματος, μετρημένο σε πόντους. Γράψτε **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Ορίζει την x-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Γράψτε **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Ορίζει την y-συντεταγμένη της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε πόντους. Γράψτε **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν-οστό όρισμα προτύπου ως αδύνατο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινό μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινό μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την εντολή C# lock() για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../../aspose.slides/shape/) ως αρχείο SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Αποθηκεύει το περιεχόμενο του [Shape](../../aspose.slides/shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Χώρος ονομάτων [Aspose::Slides::Ink](../)
* Βιβλιοθήκη [Aspose.Slides](../../)