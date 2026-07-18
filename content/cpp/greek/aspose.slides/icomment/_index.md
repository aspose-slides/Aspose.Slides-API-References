---
title: IComment
second_title: Αναφορά API του Aspose.Slides για C++
description: Αναπαριστά ένα σχόλιο σε μια διαφάνεια.
type: docs
weight: 1782
url: /el/aspose.slides/icomment/
---
## IComment κλάση

Αναπαριστά ένα σχόλιο σε μια διαφάνεια.

```cpp
class IComment : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_Author](./get_author/)() | Επιστρέφει τον συγγραφέα ενός σχολίου. Μόνο για ανάγνωση [ICommentAuthor](../icommentauthor/). |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Επιστρέφει την ώρα δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε [DateTime::MinValue](../../system/datetime/minvalue/) σημαίνει ότι η ώρα σχολίου δεν έχει οριστεί. Μόνο για ανάγνωση [System::DateTime](../../system/datetime/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IComment](./)\> [get_ParentComment](./get_parentcomment/)() | Λαμβάνει το γονικό σχόλιο. Μόνο για ανάγνωση [IComment](./). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_Position](./get_position/)() | Επιστρέφει τη θέση ενός σχολίου σε μια διαφάνεια. Μόνο για ανάγνωση [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)() | Επιστρέφει τη γονική διαφάνεια ενός σχολίου. Μόνο για ανάγνωση [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Text](./get_text/)() | Επιστρέφει το απλό κείμενο ενός σχολίου διαφάνειας. Μόνο για ανάγνωση [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που συσχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την κλειδαριά της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων για υποκατηγορίες. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία αντιγράφων για υποκατηγορίες. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| virtual void [Remove](./remove/)() | Αφαιρεί το σχόλιο και όλες τις απαντήσεις του από τη γονική συλλογή. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμεσο μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Ορίζει την ώρα δημιουργίας ενός σχολίου. Ορισμός αυτής της ιδιότητας σε [DateTime::MinValue](../../system/datetime/minvalue/) σημαίνει ότι η ώρα σχολίου δεν έχει οριστεί. Εγγραφή [System::DateTime](../../system/datetime/). |
| virtual void [set_ParentComment](./set_parentcomment/)([System::SharedPtr](../../system/sharedptr/)\<[IComment](./)\>) | Ορίζει το γονικό σχόλιο. Εγγραφή [IComment](./). |
| virtual void [set_Position](./set_position/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Ορίζει τη θέση ενός σχολίου σε μια διαφάνεια. Εγγραφή [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Text](./set_text/)([System::String](../../system/string/)) | Ορίζει το απλό κείμενο ενός σχολίου διαφάνειας. Εγγραφή [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το nth όρισμα προτύπου ως αδυνατό δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμεσου μετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμεσο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Αποτελεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την άρση κλειδαριάς της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύνατο μετρητή αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)