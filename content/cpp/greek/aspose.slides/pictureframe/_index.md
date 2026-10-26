---
title: PictureFrame
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά ένα πλαίσιο με μια εικόνα μέσα.
type: docs
weight: 4733
url: /el/aspose.slides/pictureframe/
---
## PictureFrame κλάση

Αναπαριστά ένα πλαίσιο με μια εικόνα μέσα.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Προσθέτει έναν νέο χώρο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του χώρου κράτησης σε ένα συγκεκριμένο. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Δημιουργεί και επιστρέφει έναν πίνακα των στοιχείων του shape's. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Επιστρέφει την τιμή των ρυθμίσεων του shape's στο καθορισμένο δείκτη. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Επιστρέφει μια συλλογή τιμών ρυθμίσεων του shape's. Μόνο για ανάγνωση [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Επιστρέφει το εναλλακτικό κείμενο που συνδέεται με ένα shape. Ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα shape. Ανάγνωση [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Η ιδιότητα καθορίζει πώς ένα shape θα αποτυπώθει σε λειτουργία ασπρόμαυρης εμφάνισης.. Ανάγνωση [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο shape. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Επιστρέφει τα προσαρμοσμένα δεδομένα του shape. Μόνο για ανάγνωση [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους shapes που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους shapes που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Επιστρέφει τις ιδιότητες του πλαισίου shape. Ανάγνωση [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Λαμβάνει το ύψος του shape, μετρημένο σε points. Ανάγνωση **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Καθορίζει αν το shape είναι κρυφό. Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Ανάγνωση [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Επιστρέφει τον διαχειριστή υπερσύνδεσμων. Μόνο για ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για πέρασμα του ποντικιού. Ανάγνωση [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | Καθορίζει εάν το [PictureFrame](./) είναι αντικείμενο Cameo ή όχι. Μόνο για ανάγνωση **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Λαμβάνει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Καθορίζει εάν το shape είναι ομαδοποιημένο. Μόνο για ανάγνωση **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Καθορίζει εάν το shape είναι TextHolder_PPT. Μόνο για ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους shapes που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Επιστρέφει το όνομα ενός shape. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Ανάγνωση [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Επιστρέφει έναν μοναδικό ταυτοτικό αριθμό εντός της διαφάνειας που παραμένει σταθερός για τη διάρκεια ζωής του shape και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφέρεται αξιόπιστα στο shape από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το shape είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | Επιστρέφει το αντικείμενο [PictureFillFormat](../picturefillformat/) για ένα picture frame. Μόνο για ανάγνωση [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | Επιστρέφει τις κλειδώσεις του shape. Μόνο για ανάγνωση [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Επιστρέφει το placeholder για ένα shape. Επιστρέφει null εάν το shape δεν έχει placeholder. Μόνο για ανάγνωση [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου shape. Ανάγνωση [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | Επιστρέφει την κλίμακα του ύψους (σχέση με το αρχικό μέγεθος της εικόνας) του picture frame. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | Επιστρέφει την κλίμακα του πλάτους (σχέση με το αρχικό μέγεθος της εικόνας) του picture frame. Η τιμή 1.0 αντιστοιχεί στο 100%. Ανάγνωση **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Επιστρέφει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Επιστρέφει τις κλειδώσεις του shape. Μόνο για ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Επιστρέφει το αντικείμενο στυλ του shape. Μόνο για ανάγνωση [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Επιστρέφει τη γονική διαφάνεια ενός shape. Μόνο για ανάγνωση [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες 3d εφέ για ένα shape. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους shapes που δεν έχουν ιδιότητες 3d. Μόνο για ανάγνωση [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Επιστρέφει έναν εσωτερικό, περιορισμένο σε παρουσίαση ταυτοτικό αριθμό που προορίζεται για χρήση από πρόσθετα ή άλλον κώδικα. Δεδομένου ότι αυτή η τιμή μπορεί να επαναχρησιμοποιηθεί από τον χρήστη ή προγραμματικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Λαμβάνει το πλάτος του shape, μετρημένο σε points. Ανάγνωση **float**. |
| **float** [get_X](../shape/get_x/)() override | Λαμβάνει την x-συντεταγμένη της άνω αριστερής γωνίας του shape, μετρημένη σε points. Ανάγνωση **float**. |
| **float** [get_Y](../shape/get_y/)() override | Λαμβάνει την y-συντεταγμένη της άνω αριστερής γωνίας του shape, μετρημένη σε points. Ανάγνωση **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Επιστρέφει τη θέση ενός shape στην σειρά z. Shapes[0] επιστρέφει το shape στο τέλος της σειράς z, και Shapes[Shapes.Count - 1] επιστρέφει το shape στην αρχή της σειράς z. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Επιστρέφει ένα βασικό placeholder shape (shape από τη διάταξη και/ή το master slide από το οποίο κληρονομείται το τρέχον shape). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Επιστρέφει το αντίγραφο της διαδρομής του γεωμετρικού shape. Οι συντεταγμένες είναι σχετικές με την αριστερή άνω γωνία του shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Επιστρέφει το μικρογραφικό του shape. Ο τύπος περιγράμματος μικρογραφικού [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape χρησιμοποιείται εξ ορισμού. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Επιστρέφει το μικρογραφικό του shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Λαμβάνει τα οπτικά όρια του shape υπολογισμένα από το αποδιδόμενο περιεχόμενό του. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή κλειδώματος C# lock(). Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με nullptr με αναφορά. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστης αναφοράς κατά την καθορισμένη τιμή. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Ορίζει ότι αυτό το shape δεν είναι placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ορίζει το εναλλακτικό κείμενο που συνδέεται με ένα shape. Εγγραφή [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο του εναλλακτικού κειμένου που συνδέεται με ένα shape. Εγγραφή [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Η ιδιότητα καθορίζει πώς ένα shape θα αποτυπώθει σε λειτουργία ασπρόμαυρης εμφάνισης.. Εγγραφή [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ιδιότητες του πλαισίου shape. Εγγραφή [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ορίζει το ύψος του shape, μετρημένο σε points. Εγγραφή **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Καθορίζει αν το shape είναι κρυφό. Εγγραφή **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ του ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα του ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/εγγραφή **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ορίζει το όνομα ενός shape. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή συμβολοσειρά αν χρειάζεται. Εγγραφή [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου shape. Εγγραφή [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | Ορίζει την κλίμακα του ύψους (σχέση με το αρχικό μέγεθος της εικόνας) του picture frame. Η τιμή 1.0 αντιστοιχεί στο 100%. Εγγραφή **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | Ορίζει την κλίμακα του πλάτους (σχέση με το αρχικό μέγεθος της εικόνας) του picture frame. Η τιμή 1.0 αντιστοιχεί στο 100%. Εγγραφή **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ορίζει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο shape περιστρέφεται γύρω από τον άξονα z. Μια θετική τιμή υποδηλώνει δεξιόστροφη περιστροφή· μια αρνητική τιμή υποδηλώνει αριστερόστροφη περιστροφή. Εγγραφή **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | Ορίζει το πλάτος του shape, μετρημένο σε points. Εγγραφή **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ορίζει την x-συντεταγμένη της άνω αριστερής γωνίας του shape, μετρημένη σε points. Εγγραφή **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ορίζει την y-συντεταγμένη της άνω αριστερής γωνίας του shape, μετρημένη σε points. Εγγραφή **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Ενημερώνει τη γεωμετρία του shape από το αντικείμενο [IGeometryPath](../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του shape. Αλλάζει τον τύπο του shape ([ShapeType](../shapetype/)) σε [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Ενημερώνει τη γεωμετρία του shape από πίνακα του [IGeometryPath](../igeometrypath/). Οι συντεταγμένες πρέπει να είναι σχετικές με την αριστερή άνω γωνία του shape. Αλλάζει τον τύπο του shape ([ShapeType](../shapetype/)) σε [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστης αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Καλείται απευθείας ή χρησιμοποιείται το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να αλλάξετε το [Audio](../audio/) Frame Thumbnail.

```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Προσθέτει ένα πλαίσιο ήχου στη διαφάνεια με καθορισμένη θέση και μέγεθος.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// Προσθέτει μια εικόνα στους πόρους της παρουσίασης.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// Ορίζει την εικόνα για το πλαίσιο ήχου.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Αποθηκεύει την τροποποιημένη παρουσίαση στο δίσκο
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [GeometryShape](../geometryshape/)
* Κλάση [IPictureFrame](../ipictureframe/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)