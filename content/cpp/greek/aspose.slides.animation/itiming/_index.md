---
title: ITiming
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει το χρονισμό της κίνησης.
type: docs
weight: 443
url: /el/aspose.slides.animation/itiming/
---
## ITiming κλάση

Αντιπροσωπεύει το χρονισμό της κίνησης.

```cpp
class ITiming : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σύνταξη C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Περιγράφει το ποσοστό του χρόνου του εφέ επιτάχυνσης. Ανάγνωση **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Περιγράφει εάν η κίνηση θα αναπαράγεται αυτόματα αντίστροφα μετά την προώθηση. Ανάγνωση **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Περιγράφει το ποσοστό του χρόνου του εφέ επιβράδυνσης. Ανάγνωση **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Ανάγνωση **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Καθορίζει εάν ένα εφέ θα επανεκκινήσει μετά την ολοκλήρωση. Ανάγνωση [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) το χρονοδιάγραμμα. Ανάγνωση **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. Ανάγνωση **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Περιγράφει τον τύπο του ερεθίσματος. Ανάγνωση [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό του κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατά την κατασκευή υποτύπων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατά την κατασκευή υποτύπων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Περιγράφει το ποσοστό του χρόνου του εφέ επιτάχυνσης. Εγγραφή **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Περιγράφει εάν η κίνηση θα αναπαράγεται αυτόματα αντίστροφα μετά την προώθηση. Εγγραφή **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Περιγράφει το ποσοστό του χρόνου του εφέ επιβράδυνσης. Εγγραφή **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Περιγράφει τη διάρκεια του εφέ κίνησης. Εγγραφή **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Εγγραφή **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Εγγραφή **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Εγγραφή **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Εγγραφή **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Καθορίζει εάν ένα εφέ θα επανεκκινήσει μετά την ολοκλήρωση. Εγγραφή [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επανέλθει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Εγγραφή **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) το χρονοδιάγραμμα. Εγγραφή **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Περιγράφει τον χρόνο καθυστέρησης μετά το ερέθισμα. Εγγραφή **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Περιγράφει τον τύπο του ερεθίσματος. Εγγραφή [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμη αναφορά (αντί για κοινή). Επιτρέπει την εναλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Κλήση άμεσα ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Animation](../)
* Βιβλιοθήκη [Aspose.Slides](../../)