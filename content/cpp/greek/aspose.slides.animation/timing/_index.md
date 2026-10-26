---
title: Timing
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιπροσωπεύει τον χρονισμό της κίνησης.
type: docs
weight: 625
url: /el/aspose.slides.animation/timing/
---
## Timing κλάση

Represents animation timing.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **float** [get_Accelerate](./get_accelerate/)() override | Περιγράφει το ποσοστό της διάρκειας του φαινομένου επιτάχυνσης. Ανάγνωση **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Περιγράφει αν η κίνηση θα αναπαράγεται αυτόματα σε αντίστροφη κατεύθυνση μετά την αναπαραγωγή προς τα εμπρός. Ανάγνωση **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Περιγράφει το ποσοστό της διάρκειας του φαινομένου επιβράδυνσης. Ανάγνωση **float**. |
| **float** [get_Duration](./get_duration/)() override | Περιγράφει τη διάρκεια του εφέ κίνησης. Ανάγνωση **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Ανάγνωση **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Ανάγνωση **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Ανάγνωση **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Καθορίζει αν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. Ανάγνωση [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επιστρέψει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Ανάγνωση **bool**. |
| **float** [get_Speed](./get_speed/)() override | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. Ανάγνωση **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Περιγράφει το χρόνο καθυστέρησης μετά το σκανδάλη. Ανάγνωση **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Περιγράφει τον τύπο του σκανδαλιού. Ανάγνωση [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατασκευή hash για προσαρμοσμένα αντικείμενα. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C# για κλείδωμα. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγορίων μέσω αντιγραφής. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει κάτι, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηρίων μέσω αντιγραφής. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την ορισμένη τιμή. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Περιγράφει το ποσοστό της διάρκειας του φαινομένου επιτάχυνσης. Εγγραφή **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Περιγράφει αν η κίνηση θα αναπαράγεται αυτόματα σε αντίστροφη κατεύθυνση μετά την αναπαραγωγή προς τα εμπρός. Εγγραφή **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Περιγράφει το ποσοστό της διάρκειας του φαινομένου επιβράδυνσης. Εγγραφή **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Περιγράφει τη διάρκεια του εφέ κίνησης. Εγγραφή **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Εγγραφή **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Περιγράφει τον αριθμό των επαναλήψεων του εφέ. Εγγραφή **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το τέλος της διαφάνειας. Εγγραφή **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επαναληφθεί μέχρι το επόμενο κλικ. Εγγραφή **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Καθορίζει αν ένα εφέ πρέπει να επανεκκινήσει μετά την ολοκλήρωση. Εγγραφή [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ θα επιστρέψει στην αρχή όταν ολοκληρωθεί η αναπαραγωγή. Εγγραφή **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Καθορίζει το ποσοστό με το οποίο θα επιταχυνθεί (ή θα επιβραδυνθεί) ο χρονισμός. Εγγραφή **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Περιγράφει το χρόνο καθυστέρησης μετά το σκανδάλη. Εγγραφή **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Περιγράφει τον τύπο του σκανδαλιού. Εγγραφή [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατοδείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε containers σε αδυνατή λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για απελευθέρωση. Κλήση άμεσα ή χρήση του αντικειμένου [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατοδείκτη μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατοδείκτη μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δες επίσης

* Κλάση [ITiming](../itiming/)
* Κλάση [IDOMObject](../../aspose.slides/idomobject/)
* Χώρος ονομάτων [Aspose::Slides::Animation](../)
* Βιβλιοθήκη [Aspose.Slides](../../)