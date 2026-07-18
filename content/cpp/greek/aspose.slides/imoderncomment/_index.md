---
title: IModernComment
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει ένα σχόλιο σε μια διαφάνεια.
type: docs
weight: 2965
url: /el/aspose.slides/imoderncomment/
---
## IModernComment κλάση

Αναπαριστά ένα σχόλιο σε μια διαφάνεια.

```cpp
class IModernComment : public virtual Aspose::Slides::IComment
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](../icomment/get_author/)() | Επιστρέφει τον συγγραφέα ενός σχολίου. Μόνο ανάγνωση [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](../icomment/get_createdtime/)() | Επιστρέφει την ώρα δημιουργίας ενός σχολίου. Ορίζοντας αυτήν την ιδιότητα σε [DateTime::MinValue](../../system/datetime/minvalue/) σημαίνει ότι δεν ορίζεται χρόνος σχολίου. Ανάγνωση [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\> [get_ParentComment](../icomment/get_parentcomment/)() | Λαμβάνει το γονικό σχόλιο. Ανάγνωση [IComment](../icomment/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](../icomment/get_position/)() | Επιστρέφει τη θέση ενός σχολίου σε διαφάνεια. Ανάγνωση [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)() | Επιστρέφει ένα σχήμα συσχετισμένο με το σχόλιο. Μόνο ανάγνωση [IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](../icomment/get_slide/)() | Επιστρέφει τη γονική διαφάνεια ενός σχολίου. Μόνο ανάγνωση [ISlide](../islide/). |
| virtual [ModernCommentStatus](../moderncommentstatus/) [get_Status](./get_status/)() | Επιστρέφει την κατάσταση του σχολίου. Ανάγνωση [ModernCommentStatus](../moderncommentstatus/). |
| virtual [System::String](../../system/string/) [get_Text](../icomment/get_text/)() | Επιστρέφει το απλό κείμενο ενός σχολίου διαφάνειας. Ανάγνωση [System::String](../../system/string/). |
| virtual **int32_t** [get_TextSelectionLength](./get_textselectionlength/)() | Επιστρέφει το μήκος επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο συνδέεται με [AutoShape](../autoshape/). Ανάγνωση **int32_t**. |
| virtual **int32_t** [get_TextSelectionStart](./get_textselectionstart/)() | Επιστρέφει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο συνδέεται με [AutoShape](../autoshape/). Ανάγνωση **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή υποκατηγοριών. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| virtual void [Remove](../icomment/remove/)() | Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_CreatedTime](../icomment/set_createdtime/)([System::DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας ενός σχολίου. Ορίζοντας αυτήν την ιδιότητα σε [DateTime::MinValue](../../system/datetime/minvalue/) σημαίνει ότι δεν ορίζεται χρόνος σχολίου. Εγγραφή [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](../icomment/set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>) | Ορίζει το γονικό σχόλιο. Εγγραφή [IComment](../icomment/). |
| virtual void [set_Position](../icomment/set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Ορίζει τη θέση ενός σχολίου σε διαφάνεια. Εγγραφή [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Status](./set_status/)([ModernCommentStatus](../moderncommentstatus/)) | Ορίζει την κατάσταση του σχολίου. Εγγραφή [ModernCommentStatus](../moderncommentstatus/). |
| virtual void [set_Text](../icomment/set_text/)([System::String](../../system/string/)) | Ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Εγγραφή [System::String](../../system/string/). |
| virtual void [set_TextSelectionLength](./set_textselectionlength/)(**int32_t**) | Ορίζει το μήκος επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο συνδέεται με [AutoShape](../autoshape/). Εγγραφή **int32_t**. |
| virtual void [set_TextSelectionStart](./set_textselectionstart/)(**int32_t**) | Ορίζει τη θέση εκκίνησης της επιλογής κειμένου σε πλαίσιο κειμένου εάν το σχόλιο συνδέεται με [AutoShape](../autoshape/). Εγγραφή **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη δείκτη (αντί για κοινόχρηστη). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την αποδέσμευση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
auto modernComment = newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Δείτε επίσης

* Κλάση [IComment](../icomment/)
* Ονομαχώρος [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)