---
title: OleObjectFrame
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει ένα αντικείμενο OLE σε μια διαφάνεια.
type: docs
weight: 4603
url: /el/aspose.slides/oleobjectframe/
---
## OleObjectFrame κλάση

Αντιπροσωπεύει ένα αντικείμενο OLE σε μια διαφάνεια.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Προσθέτει ένα νέο σύμβολο κράτησης εάν δεν υπάρχει και ορίζει τις ιδιότητες του σύμβολου σε ένα καθορισμένο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση σημειακών αριθμών σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση σημειακών αριθμών σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, ακόμα και με NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Επιστρέφει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Επιστρέφει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Διαβάστε [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης.. Διαβάστε [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Επιστρέφει τον αριθμό των σημείων σύνδεσης στο σχήμα. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Επιστρέφει τα προσαρμοσμένα δεδομένα του σχήματος. Μόνο για ανάγνωση [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Επιστρέφει το αντικείμενο [EffectFormat](../effectformat/) που περιέχει εφέ εικονοστοιχείων που εφαρμόζονται σε ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες εφέ. Μόνο για ανάγνωση [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | Λαμβάνει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. Διαβάστε [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Επιστρέφει το όνομα αρχείου του ενσωματωμένου αντικειμένου OLE |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Επιστρέφει τη διαδρομή του ενσωματωμένου αντικειμένου OLE |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Επιστρέφει το αντικείμενο [FillFormat](../fillformat/) που περιέχει ιδιότητες μορφοποίησης γεμίσματος για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γεμίσματος. Μόνο για ανάγνωση [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Επιστρέφει τις ιδιότητες του πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο για ανάγνωση [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Λαμβάνει το ύψος του σχήματος, μετρημένο σε σημεία. Ανάγνωση **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Καθορίζει αν το σχήμα είναι κρυμμένο. Ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικού. Διαβάστε [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Επιστρέφει τον διαχειριστή υπερσυνδέσμων. Μόνο για ανάγνωση [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Επιστρέφει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Διαβάστε [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Λαμβάνει την επιλογή 'Mark as decorative'. Ανάγνωση/Εγγραφή **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Καθορίζει εάν το σχήμα είναι ομαδοποιημένο. Μόνο για ανάγνωση **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Ανάγνωση **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Καθορίζει εάν ένα αντικείμενο είναι συνδεδεμένο με εξωτερικό αρχείο. Μόνο για ανάγνωση **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Καθορίζει εάν το σχήμα είναι TextHolder_PPT. Μόνο για ανάγνωση **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Επιστρέφει το αντικείμενο [LineFormat](../lineformat/) που περιέχει ιδιότητες μορφοποίησης γραμμής για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες γραμμής. Μόνο για ανάγνωση [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί σύντομο όνομα αρχείου. Μόνο για ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Επιστρέφει τη σχετική διαδρομή σε ένα συνδεδεμένο αρχείο εάν υπάρχει, διαφορετικά επιστρέφει κενή συμβολοσειρά. Μόνο για ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Επιστρέφει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή τιμή συμβολοσειράς εάν χρειάζεται. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Επιστρέφει το όνομα ενός αντικειμένου. Διαβάστε [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο για ανάγνωση [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Επιστρέφει ένα μοναδικό αναγνωριστικό περιορισμένο στη διαφάνεια που παραμένει σταθερό για τη διάρκεια του σχήματος και επιτρέπει στο PowerPoint ή σε κώδικα interop να αναφεράται αξιόπιστα στο σχήμα από οπουδήποτε στο έγγραφο. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Επιστρέφει το γονικό αντικείμενο [GroupShape](../groupshape/) εάν το σχήμα είναι ομαδοποιημένο. Διαφορετικά επιστρέφει null. Μόνο για ανάγνωση [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Επιστρέφει το placeholder για ένα σχήμα. Επιστρέφει null εάν το σχήμα δεν έχει placeholder. Μόνο για ανάγνωση [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Επιστρέφει την γονική παρουσίαση μιας διαφάνειας. Μόνο για ανάγνωση [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Επιστρέφει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Διαβάστε [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Επιστρέφει τον αριθμό των μοιρών κατά τις οποίες το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Ανάγνωση **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Επιστρέφει τα κλειδώματα του σχήματος. Μόνο για ανάγνωση [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Επιστρέφει τη γονική διαφάνεια ενός σχήματος. Μόνο για ανάγνωση [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Επιστρέφει το αντικείμενο ιδιοτήτων γεμίσματος εικόνας OleObject. Μόνο για ανάγνωση [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | Επιστρέφει τον τίτλο για το εικονίδιο OleObject. Διαβάστε [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Επιστρέφει το αντικείμενο [ThreeDFormat](../threedformat/) που περιέχει ιδιότητες 3d εφέ για ένα σχήμα. Σημείωση: μπορεί να επιστρέψει null για ορισμένους τύπους σχημάτων που δεν έχουν ιδιότητες 3d. Μόνο για ανάγνωση [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Επιστρέφει έναν εσωτερικό, περιορισμένο στην παρουσίαση, αναγνωριστικό προορισμένο για χρήση από πρόσθετα ή άλλον κώδικα. Επειδή αυτή η τιμή μπορεί να ανατεθεί ξανά από τον χρήστη ή προγραμματιστικά, δεν πρέπει να θεωρείται μόνιμο μοναδικό κλειδί. Μόνο για ανάγνωση **uint32_t**. Δείτε επίσης [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίγει ή εκτυπώνεται. Ανάγνωση **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Λαμβάνει το πλάτος του σχήματος, μετρημένο σε σημεία. Ανάγνωση **float**. |
| **float** [get_X](../shape/get_x/)() override | Λαμβάνει τη συντεταγμένη x του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση **float**. |
| **float** [get_Y](../shape/get_y/)() override | Λαμβάνει τη συντεταγμένη y του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Ανάγνωση **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Επιστρέφει τη θέση ενός σχήματος στη σειρά z. Η Shapes[0] επιστρέφει το σχήμα στο πίσω μέρος της σειράς z, και η Shapes[Shapes.Count - 1] επιστρέφει το σχήμα στο μπροστινό μέρος της σειράς z. Μόνο για ανάγνωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Επιστρέφει ένα βασικό σχήμα placeholder (σχήμα από τη διάταξη και/ή την κύρια διαφάνεια από το οποίο κληρονομείται το τρέχον σχήμα). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Επιστρέφει μικρογραφία σχήματος. Ο τύπος ορίων μικρογραφίας σχήματος [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) χρησιμοποιείται εξ ορισμού. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Επιστρέφει μικρογραφία σχήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποπειραμένο περιεχόμενό του. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής των υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή κατασκευής των υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Ορίζει ότι αυτό το σχήμα δεν είναι placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ορίζει το εναλλακτικό κείμενο που συσχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο του εναλλακτικού κειμένου που συσχετίζεται με ένα σχήμα. Εγγραφή [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Η ιδιότητα καθορίζει πώς θα αποδίδεται ένα σχήμα σε λειτουργία ασπρόμαυρης εμφάνισης.. Εγγραφή [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ορίζει το ύψος του σχήματος, μετρημένο σε σημεία. Εγγραφή **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Καθορίζει εάν το σχήμα είναι κρυμμένο. Εγγραφή **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για κλικ ποντικού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ορίζει τον υπερσύνδεσμο που ορίζεται για πέρασμα ποντικιού. Εγγραφή [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ορίζει την επιλογή 'Mark as decorative'. Ανάγνωση/Εγγραφή **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Καθορίζει εάν ένα αντικείμενο είναι ορατό ως εικονίδιο. Εγγραφή **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Επιστρέφει τη πλήρη διαδρομή σε ένα συνδεδεμένο αρχείο. Θα χρησιμοποιηθεί μακρύ όνομα αρχείου. Εγγραφή [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ορίζει το όνομα ενός σχήματος. Πρέπει να μην είναι null. Χρησιμοποιήστε κενή τιμή συμβολοσειράς εάν χρειάζεται. Εγγραφή [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Ορίζει το όνομα ενός αντικειμένου. Εγγραφή [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Επιστρέφει το ProgID ενός αντικειμένου. Μόνο για ανάγνωση [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ορίζει τις ακατέργαστες ιδιότητες του πλαισίου σχήματος. Εγγραφή [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ορίζει τον αριθμό των μοιρών που το συγκεκριμένο σχήμα περιστρέφεται γύρω από τον άξονα z. Θετική τιμή υποδεικνύει δεξιόστροφη περιστροφή· αρνητική τιμή υποδεικνύει αριστερόστροφη περιστροφή. Εγγραφή **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | Ορίζει τον τίτλο για το εικονίδιο OleObject. Εγγραφή [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Καθορίζει εάν το συνδεδεμένο ενσωματωμένο αντικείμενο ενημερώνεται αυτόματα όταν η παρουσίαση ανοίξει ή εκτυπωθεί. Εγγραφή **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Ορίζει το πλάτος του σχήματος, μετρημένο σε σημεία. Εγγραφή **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ορίζει τη συντεταγμένη x του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Εγγραφή **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ορίζει τη συντεταγμένη y του πάνω-αριστερού γωνιακού σημείου του σχήματος, μετρημένη σε σημεία. Εγγραφή **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | Ορίζει πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε δοχείων σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν θα πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Αποθηκεύει το περιεχόμενο του [Shape](../shape/) ως αρχείο SVG. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσεγγίζετε τα πλαίσια OLE Object.

```cpp
// Φορτώνει το PPTX σε ένα αντικείμενο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// Πρόσβαση στην πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);
// Μετατρέπει το σχήμα σε OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// Διαβάζει το αντικείμενο OLE και το γράφει στο δίσκο
if (oleObjectFrame != nullptr)
{
    // Λαμβάνει τα δεδομένα ενσωματωμένου αρχείου
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Λαμβάνει την επέκταση του ενσωματωμένου αρχείου
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Δημιουργεί μια διαδρομή για αποθήκευση του εξαγόμενου αρχείου
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Αποθηκεύει τα εξαγόμενα δεδομένα
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Δείτε επίσης

* Κλάση [GraphicalObject](../graphicalobject/)
* Κλάση [IOleObjectFrame](../ioleobjectframe/)
* Ονομαχώρος [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)