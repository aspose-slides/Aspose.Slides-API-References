---
title: ISlideShowTransition
second_title: Αναφορά API του Aspose.Slides για C++
description: Αντιπροσωπεύει τη μετάβαση παρουσίασης διαφανειών.
type: docs
weight: 3810
url: /el/aspose.slides/islideshowtransition/
---
## ISlideShowTransition κλάση


Αντιπροσωπεύει τη μετάβαση παρουσίασης διαφανειών.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία [Object.Equals](../../system/object/equals/) της C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν, σύμφωνα με IEC 60559:1989, το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Προσομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα ακόμη και αν, σύμφωνα με IEC 60559:1989, το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα προχωρήσει στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Ανάγνωση **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν δεν καθοριστεί αυτό το χαρακτηριστικό, θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγνωση **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, θεωρείται τιμή true. Ανάγνωση **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Λαμβάνει τη διάρκεια του εφέ μετάβασης της διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγνωση **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Επιστρέφει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Καθορίζει εάν ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, η δημιουργική εφαρμογή ειδοποιείται για να ελέγξει το χαρακτηριστικό name που ορίστηκε για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή UI όπως απαιτείται. Ανάγνωση **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Καθορίζει ένα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Το [ISlideShowTransition::set_Sound](./set_sound/) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Ανάγνωση [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Τύπος μετάβασης. Ανάγνωση [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) εμφανίζει την τιμή της μετάβασης. Μόνο ανάγνωση [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περιπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περιπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρο αναφοράς κατά τη συγκεκριμένη τιμή. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα προχωρήσει στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Εγγραφή **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί μαζί με το χαρακτηριστικό advClick. Εάν δεν καθοριστεί, θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Γράφει **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν δεν καθοριστεί, θεωρείται true. Γράφει **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Ορίζει τη διάρκεια του εφέ μετάβασης της διαφάνειας σε χιλιοστά του δευτερολέπτου. Γράφει **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Ορίζει τα ενσωματωμένα δεδομένα ήχου. Γράφει [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Καθορίζει εάν ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, η δημιουργική εφαρμογή ειδοποιείται για να ελέγξει το χαρακτηριστικό name που ορίστηκε για αυτόν τον ήχο στη λίστα ενσωματωμένων ήχων και μπορεί να εμφανίσει προσαρμοσμένο όνομα ή UI όπως απαιτείται. Γράφει **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Γράφει **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Γράφει [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Καθορίζει ένα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Το [ISlideShowTransition::set_Sound](./set_sound/) πρέπει να οριστεί για να ληφθεί ή να οριστεί το όνομα ήχου. Γράφει [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί κατά τη μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Γράφει [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Τύπος μετάβασης. Γράφει [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει τη δομή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την απελευθέρωση του statement lock() της C#. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται άμεσα· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)