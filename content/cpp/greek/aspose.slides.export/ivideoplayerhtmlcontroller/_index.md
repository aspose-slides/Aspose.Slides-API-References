---
title: IVideoPlayerHtmlController
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αυτή η κλάση επιτρέπει την εξαγωγή βίντεο και αρχείων ήχου σε HTML
type: docs
weight: 508
url: /el/aspose.slides.export/ivideoplayerhtmlcontroller/
---
## IVideoPlayerHtmlController κλάση


Αυτή η κλάση επιτρέπει την εξαγωγή βίντεο και αρχείων ήχου σε HTML

```cpp
class IVideoPlayerHtmlController : public Aspose::Slides::Export::IHtmlFormattingController,
                                   public Aspose::Slides::Export::ISvgShapeFormattingController,
                                   public Aspose::Slides::Export::ILinkEmbedController
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρ' όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual void [FormatShape](../isvgshapeformattingcontroller/formatshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShape](../isvgshape/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Αυτή η συνάρτηση καλείται πριν από τη μετατροπή σχήματος σε SVG για να επιτρέψει στον χρήστη τον έλεγχο του τελικού SVG. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Επιστρέφει τη δομή δεδομένων μετρητή αναφορών που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual [LinkEmbedDecision](../linkembeddecision/) [GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/), [System::String](../../system/string/), [System::String](../../system/string/)) | Καθορίζει πού πρέπει να αποθηκευτεί το αντικείμενο. Αυτή η μέθοδος καλείται μία φορά για κάθε αναγνωριστικό αντικειμένου. Δεν υπάρχει εγγύηση ότι δεν θα υπάρχουν δύο αντικείμενα με τα ίδια δεδομένα, semanticName και contentType αλλά διαφορετικό αναγνωριστικό. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Επιστρέφει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::String](../../system/string/) [GetUrl](../ilinkembedcontroller/geturl/)(**int32_t**, **int32_t**) | Επιστρέφει ένα URL σε εξωτερικό αντικείμενο. Αυτή η μέθοδος πάντα καλείται αν [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) επέστρεψε [LinkEmbedDecision::Link](../linkembeddecision/) και μπορεί να κληθεί αν [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) επέστρεψε [LinkEmbedDecision::Embed](../linkembeddecision/) αλλά η ενσωμάτωση είναι αδύνατη. Μπορεί να κληθεί πολλαπλές φορές για το ίδιο αναγνωριστικό αντικειμένου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο είναι ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί τη δήλωση κλειδώματος C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με αναφορά σε nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [SaveExternal](../ilinkembedcontroller/saveexternal/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Αποθηκεύει εξωτερικό αντικείμενο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει τη μετατροπή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Επιστρέφει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκεύασμα C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδέσμευση του C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual void [WriteDocumentEnd](../ihtmlformattingcontroller/writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | Καλείται για την καταγραφή του υποσέλιδου του αρχείου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| virtual void [WriteDocumentStart](../ihtmlformattingcontroller/writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | Καλείται για την καταγραφή της κεφαλίδας του αρχείου html. Καλείται μία φορά ανά μετατροπή παρουσίασης. |
| virtual void [WriteShapeEnd](../ihtmlformattingcontroller/writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Καλείται πριν από τη μετατροπή σχήματος. Καλείται μία φορά για κάθε σχήμα. Αν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η δημιουργία εικόνας τρέχουσας διαφάνειας ολοκληρώνεται, το προστιθέμενο τμήμα html ενσωματώνεται και νέα εικόνα ξεκινά πάνω από την προηγούμενη. |
| virtual void [WriteShapeStart](../ihtmlformattingcontroller/writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Καλείται πριν από τη μετατροπή σχήματος. Καλείται μία φορά για κάθε σχήμα. Αν αυτή η συνάρτηση γράψει κάτι στον δημιουργό, η δημιουργία εικόνας τρέχουσας διαφάνειας ολοκληρώνεται, το προστιθέμενο τμήμα html ενσωματώνεται και νέα εικόνα ξεκινά πάνω από την προηγούμενη. |
| virtual void [WriteSlideEnd](../ihtmlformattingcontroller/writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | Καλείται για την καταγραφή του υποσέλιδου της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| virtual void [WriteSlideStart](../ihtmlformattingcontroller/writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | Καλείται για την καταγραφή της κεφαλίδας της διαφάνειας html. Καλείται μία φορά για κάθε διαφάνεια. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [IHtmlFormattingController](../ihtmlformattingcontroller/)
* Κλάση [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)
* Κλάση [ILinkEmbedController](../ilinkembedcontroller/)
* Ονοματοχώρος [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)