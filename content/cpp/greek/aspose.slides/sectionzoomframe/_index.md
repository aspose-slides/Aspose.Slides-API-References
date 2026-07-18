---
title: SectionZoomFrame
second_title: Aspose.Slides για την αναφορά API C++
description: Αναπαριστά ένα αντικείμενο Section Zoom σε μια διαφάνεια.
type: docs
weight: 5045
url: /el/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame κλάση

Represents a [Section](../section/) Zoom object in a slide.

```cpp
class SectionZoomFrame : public Aspose::Slides::ZoomObject,
                         public virtual Aspose::Slides::ISectionZoomFrame
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Προσθέτει ένα νέο placeholder εάν δεν υπάρχει και ορίζει τις ιδιότητες του placeholder σε ένα συγκεκριμένο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Επιστρέφει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποδίδεται σε λειτουργία ασπρόμαυρης προβολής. Διαβάστε [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) το οποίο περιέχει εφέ pixel που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένα είδη σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο-ανάγνωση [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Επιστρέφει το [FillFormat](../fillformat/) αντικείμενο που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένα είδη σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Επιστρέφει τις ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο-ανάγνωση [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Λαμβάνει το ύψος του σχήματος, μετρημένο σε points. Μόνο-ανάγνωση **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Λαμβάνει εάν το σχήμα είναι κρυμμένο. Μόνο-ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Επιστρέφει τον διαχειριστή υπερσυνδέσμου. Μόνο-ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για hover ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Λαμβάνει τον τύπο εικόνας ενός αντικειμένου zoom. Διαβάστε [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Λαμβάνει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένα είδη σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο-ανάγνωση [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Επιστρέφει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειαστεί. Διαβάστε [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Επιστρέφει ένα μοναδικό αναγνωριστικό σε επίπεδο διαφάνειας που παραμένει σταθερό κατά τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο-ανάγνωση [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο-ανάγνωση [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Λαμβάνει τη συμπεριφορά πλοήγησης στην προβολή διαφανειών. Μόνο-ανάγνωση **bool**. Προεπιλεγμένη τιμή: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Επιστρέφει τον αριθμό των μοιρών με τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόμετρη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόμετρη περιστροφή. Μόνο-ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο-ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Λαμβάνει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Μόνο-ανάγνωση **bool**. Προεπιλεγμένη τιμή: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο-ανάγνωση [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() override | Λαμβάνει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Zoom [Section](../section/). Διαβάστε [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιλαμβάνει τις ιδιότητες 3δ εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένα είδη σχημάτων που δεν έχουν ιδιότητες 3δ. Μόνο-ανάγνωση [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Λαμβάνει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Μόνο-ανάγνωση **float**. Προεπιλεγμένη τιμή: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Επιστρέφει ένα εσωτερικό, σε επίπεδο παρουσίασης, αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλον κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανατοποθετηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Λαμβάνει το πλάτος του σχήματος, μετρημένο σε points. Μόνο-ανάγνωση **float**. |
| **float** [get_X](../shape/get_x/)() override | Λαμβάνει την συντεταγμένη x του πάνω-αριστερού γωνίας του σχήματος, μετρημένη σε points. Μόνο-ανάγνωση **float**. |
| **float** [get_Y](../shape/get_y/)() override | Λαμβάνει την συντεταγμένη y του πάνω-αριστερού γωνίας του σχήματος, μετρημένη σε points. Μόνο-ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Λαμβάνει την εικόνα για το αντικείμενο zoom. Διαβάστε [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Επιστρέφει τη θέση ενός σχήματος στη διαταγή z. Shapes[0] επιστρέφει το σχήμα στο τέλος της διαταγής z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στην αρχή της διαταγής z. Μόνο-ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Επιστρέφει ένα βασικό placeholder σχήμα (σχήμα από τη διάταξη και/ή τη διαφάνεια master από την οποία κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογίας της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Επιστρέφει το μικρογραφία του σχήματος. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) τύπος ορίων μικρογραφίας σχήματος χρησιμοποιείται από προεπιλογή. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Επιστρέφει το μικρογραφία του σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογίας της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοσμένο περιεχόμενό του. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου όπως περιγράφεται από targetType. Αναλογίας του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση C# lock() για κλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογίας της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευάστης αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεσώτης ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr κατά αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Η ιδιότητα καθορίζει πώς ένα σχήμα θα αποδίδεται σε λειτουργία ασπρόμαυρης προβολής. Γράψτε [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ορίζει το ύψος του σχήματος, μετρημένο σε points. Γράψτε **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Καθορίζει εάν το σχήμα είναι κρυμμένο. Γράψτε **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικιού. Γράψτε [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για hover ποντικιού. Γράψτε [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Ορίζει τον τύπο εικόνας ενός αντικειμένου zoom. Γράψτε [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ορίζει την επιλογή 'Mark as decorative'. Ανάγωση/εγγραφή **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειαστεί. Γράψτε [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Ορίζει τη συμπεριφορά πλοήγησης στην προβολή διαφανειών. Γράψτε **bool**. Προεπιλεγμένη τιμή: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ορίζει τον αριθμό των μοιρών με τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδεικνύει δεξιόμετρη περιστροφή· μια αρνητική τιμή υποδεικνύει αριστερόμετρη περιστροφή. Γράψτε **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε **bool**. Προεπιλεγμένη τιμή: true |
| void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | Ορίζει το αντικείμενο ενότητας στο οποίο συνδέεται το αντικείμενο Zoom [Section](../section/). Γράψτε [ISection](../isection/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε **float**. Προεπιλεγμένη τιμή: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Ορίζει το πλάτος του σχήματος, μετρημένο σε points. Γράψτε **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ορίζει την συντεταγμένη x του πάνω-αριστερού γωνίας του σχήματος, μετρημένη σε points. Γράψτε **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ορίζει την συντεταγμένη y του πάνω-αριστερού γωνίας του σχήματος, μετρημένη σε points. Γράψτε **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Ορίζει την εικόνα για το αντικείμενο zoom. Γράψτε [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογίας της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το C# lock() για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [ZoomObject](../zoomobject/)
* Κλάση [ISectionZoomFrame](../isectionzoomframe/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)