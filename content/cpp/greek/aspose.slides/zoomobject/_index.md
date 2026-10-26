---
title: ZoomObject
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά ένα αντικείμενο Zoom σε μια διαφάνεια.
type: docs
weight: 5591
url: /el/aspose.slides/zoomobject/
---
## ZoomObject κλάση

Αναπαριστά ένα αντικείμενο Zoom σε μια διαφάνεια.

```cpp
class ZoomObject : public Aspose::Slides::GraphicalObject,
                   public virtual Aspise::Slides::IZoomObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Προσθέτει ένα νέο σύμβολο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολου κράτησης σε ένα καθορισμένο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικές χρήσεις. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Επιστρέφει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Διαβάστε [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο-ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο-ανάγνωση [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες εφέ. Μόνο-ανάγνωση [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες γεμίσματος. Μόνο-ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Επιστρέφει τις ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Παίρνει το ύψος του σχήματος, μετρημένο σε σημεία. Διαβάστε **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Καθορίζει εάν το σχήμα είναι κρυμμένο. Διαβάστε **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο-ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() override | Παίρνει τον τύπο εικόνας ενός αντικειμένου Zoom. Διαβάστε [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Παίρνει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο-ανάγνωση **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο-ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες γραμμής. Μόνο-ανάγνωση [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Επιστρέφει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Διαβάστε [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια ζωής του σχήματος και επιτρέπει στο PowerPoint ή στον κώδικα διασύνδεσης να αναφέρεται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο-ανάγνωση [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Επιστρέφει το σύμβολο κράτησης για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει σύμβολο κράτησης. Μόνο-ανάγνωση [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο-ανάγνωση [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](./get_returntoparent/)() override | Παίρνει τη συμπεριφορά πλοήγησης στην παρουσίαση. Διαβάστε **bool**. Προεπιλεγμένη τιμή: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Επιστρέφει τον αριθμό των μοιρών κατά τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Διαβάστε **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Επιστρέφει τις κλειδώσεις του σχήματος. Μόνο-ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](./get_showbackground/)() override | Παίρνει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Διαβάστε **bool**. Προεπιλεγμένη τιμή: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο-ανάγνωση [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν διαθέτουν ιδιότητες 3d. Μόνο-ανάγνωση [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](./get_transitionduration/)() override | Παίρνει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Διαβάστε **float**. Προεπιλεγμένη τιμή: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Επιστρέφει ένα εσωτερικό, περιορισμένο στην παρουσίαση αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλο κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επανεκχωρηθεί από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο-ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Παίρνει το πλάτος του σχήματος, μετρημένο σε σημεία. Διαβάστε **float**. |
| **float** [get_X](../shape/get_x/)() override | Παίρνει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Διαβάστε **float**. |
| **float** [get_Y](../shape/get_y/)() override | Παίρνει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Διαβάστε **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() override | Παίρνει την εικόνα για το αντικείμενο zoom. Διαβάστε [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο-ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Επιστρέφει ένα βασικό σχήμα σύμβολου κράτησης (σχήμα από τη διάταξη και/ή τη διαφάνεια προτύπου από το οποίο κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ορίων μικρογραφίας [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) του σχήματος χρησιμοποιείται προεπιλεγμένα. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Επιστρέφει τη μικρογραφία του σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Παίρνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει πράγματίτι, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει πράγματίτι, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει, με αναφορά, αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Ορίζει ότι αυτό το σχήμα δεν είναι σύμβολο κράτησης. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ορίζει το εναλλακτικό κείμενο που σχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο του εναλλακτικού κειμένου που σχετίζεται με ένα σχήμα. Γράψτε [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Η ιδιότητα καθορίζει πώς θα αποτυπώνεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης. Γράψτε [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Γράψτε **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Καθορίζει εάν το σχήμα είναι κρυμμένο. Γράψτε **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικού. Γράψτε [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικού. Γράψτε [IHyperlink](../ihyperlink/). |
| void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Ορίζει τον τύπο εικόνας ενός αντικειμένου zoom. Γράψτε [ZoomImageType](../zoomimagetype/). Προεπιλεγμένη τιμή: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά εάν χρειάζεται. Γράψτε [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου του σχήματος. Γράψτε [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](./set_returntoparent/)(**bool**) override | Ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Γράψτε **bool**. Προεπιλεγμένη τιμή: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ορίζει τον αριθμό των μοιρών κατά τον οποίο το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Γράψτε **float**. |
| void [set_ShowBackground](./set_showbackground/)(**bool**) override | Ορίζει την τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε **bool**. Προεπιλεγμένη τιμή: true |
| void [set_TransitionDuration](./set_transitionduration/)(**float**) override | Ορίζει τη διάρκεια της μετάβασης μεταξύ Zoom και διαφάνειας. Γράψτε **float**. Προεπιλεγμένη τιμή: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Γράψτε **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ορίζει τη συντεταγμένη x της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Γράψτε **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ορίζει τη συντεταγμένη y της πάνω αριστερής γωνίας του σχήματος, μετρημένη σε σημεία. Γράψτε **float**. |
| void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Ορίζει την εικόνα για το αντικείμενο zoom. Γράψτε [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [GraphicalObject](../graphicalobject/)
* Κλάση [IZoomObject](../izoomobject/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)