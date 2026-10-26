---
title: SlideShowTransition
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τη μετάβαση παρουσίασης διαφανειών.
type: docs
weight: 404
url: /el/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition κλάση


Represents slide show transition.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν τα δύο [SlideShowTransition](./) αντικείμενα είναι ίσα. Ανάγνωση/εγγραφή **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα παρ'ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaNs θεωρούνται ίσα παρ'ότι σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα προχωρήσει στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Ανάγνωση **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί σε συνδυασμό με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Ανάγωση **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι η τιμή είναι true. Ανάγωση **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Λαμβάνει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Ανάγωση **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Επιστρέφει τα ενσωματωμένα δεδομένα ήχου. Ανάγνωση [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η εφαρμογή δημιουργίας ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει καθοριστεί για αυτόν τον ήχο στη λίστα των ενσωματωμένων ήχων και μπορεί, εφόσον χρειάζεται, να προβάλλει προσαρμοσμένο όνομα ή διεπαφή χρήστη. Ανάγνωση **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Ανάγνωση **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Ανάγνωση [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Το [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) πρέπει να έχει ανατεθεί για να ληφθεί ή οριστεί το όνομα του ήχου. Ανάγηση [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί όταν γίνεται μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Ανάγνωση [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Τύπος μετάβασης. Ανάγνωση [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) εμφανίζει την τιμή μετάβασης. Μόνο-ανάγνωση [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Λειτουργεί ως συνάρτηση κατακερματισμού για συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από το targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περιπτωσιολογία string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Εξειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περιπτωσιολογία strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Αυτό το χαρακτηριστικό καθορίζει εάν η παρουσίαση θα προχωρήσει στην επόμενη διαφάνεια μετά από κάποιο χρόνο. Εγγραφή **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Καθορίζει το χρόνο, σε χιλιοστά του δευτερολέπτου, μετά τον οποίο πρέπει να ξεκινήσει η μετάβαση. Αυτή η ρύθμιση μπορεί να χρησιμοποιηθεί σε συνδυασμό με το χαρακτηριστικό advClick. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι δεν θα γίνει αυτόματη προώθηση. Εγγραφή **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Καθορίζει εάν ένα κλικ του ποντικιού θα προχωρήσει τη διαφάνεια ή όχι. Εάν αυτό το χαρακτηριστικό δεν καθοριστεί, τότε θεωρείται ότι η τιμή είναι true. Εγγραφή **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Ορίζει τη διάρκεια του εφέ μετάβασης διαφάνειας σε χιλιοστά του δευτερολέπτου. Εγγραφή **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Ορίζει τα ενσωματωμένα δεδομένα ήχου. Εγγραφή [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Καθορίζει εάν αυτός ο ήχος είναι ενσωματωμένος ή όχι. Εάν αυτό το χαρακτηριστικό οριστεί σε true, τότε η εφαρμογή δημιουργίας ειδοποιείται να ελέγξει το χαρακτηριστικό name που έχει καθοριστεί για αυτόν τον ήχο στη λίστα των ενσωματωμένων ήχων και μπορεί, εφόσον χρειάζεται, να προβάλλει προσαρμοσμένο όνομα ή διεπαφή χρήστη. Εγγραφή **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Αυτό το χαρακτηριστικό καθορίζει εάν ο ήχος θα επαναλαμβάνεται μέχρι να συμβεί το επόμενο ηχητικό γεγονός στην παρουσίαση. Εγγραφή **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Ορίζει ή επιστρέφει τη λειτουργία ήχου για τη μετάβαση διαφάνειας. Εγγραφή [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Καθορίζει ένα ανθρώπινα αναγνώσιμο όνομα για τον ήχο της μετάβασης. Το [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) πρέπει να έχει ανατεθεί για να ληφθεί ή οριστεί το όνομα του ήχου. Εγγραφή [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Καθορίζει την ταχύτητα μετάβασης που θα χρησιμοποιηθεί όταν γίνεται μετάβαση από την τρέχουσα διαφάνεια στην επόμενη. Εγγραφή [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Τύπος μετάβασης. Εγγραφή [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Δείτε επίσης

* Κλάση [DomObject](../../aspose.slides/domobject/)
* Κλάση [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Namespace [Aspose::Slides::SlideShow](../)
* Library [Aspose.Slides](../../)