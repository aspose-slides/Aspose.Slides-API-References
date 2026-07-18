---
title: Hyperlink
second_title: Aspose.Slides για αναφορά API C++
description: Αναπαριστά έναν υπερσύνδεσμο.
type: docs
weight: 1236
url: /el/aspose.slides/hyperlink/
---
## Hyperlink κλάση


Represents a hyperlink.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Καθορίζει εάν τα δύο [Hyperlink](./) στιγμιότυπα είναι ίσα. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία του C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C#, όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | Επιστρέφει τον τύπο της ενέργειας του [Hyperlink](./). Μόνο για ανάγνωση [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | Αναπαριστά την προέλευση του χρώματος του υπερσυνδέσμου - είτε στυλ είτε μορφή τμήματος. Ανάγνωση [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | Επιστρέφει έναν υπερσύνδεσμο που λήγει την παρουσίαση. Μόνο για ανάγνωση [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | Καθορίζει το εξωτερικό URL. Μόνο για ανάγνωση [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | Αναπαριστά έναν υπερσύνδεσμο που έχει οριστεί για αυτό το τμήμα χωρίς να λαμβάνει υπόψη το πραγματικό περιεχόμενο του τμήματος. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | Επιστρέφει έναν υπερσύνδεσμο στην πρώτη διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. Ανάγνωση **bool**. |
| **bool** [get_History](./get_history/)() override | Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβαλλόμενων υπερσυνδέσμων όταν κληθεί. Ανάγνωση **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία διαφάνεια της παρουσίασης. Μόνο για ανάγνωση [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | Επιστρέφει έναν υπερσύνδεσμο στην τελευταία προβλεπόμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | Επιστρέφει έναν ειδικό υπερσύνδεσμο "αναπαραγωγής αρχείου μέσων". Χρησιμοποιείται στο [AudioFrame](../audioframe/) και στο [VideoFrame](../videoframe/). Μόνο για ανάγνωση [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | Επιστρέφει έναν υπερσύνδεσμο στην επόμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | Επιστρέφει έναν ειδικό υπερσύνδεσμο "να μη κάνει τίποτα". Μόνο για ανάγνωση [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει το γονικό [IPresentationComponent](../ipresentationcomponent/). Μόνο για ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | Επιστρέφει έναν υπερσύνδεσμο στην προηγούμενη διαφάνεια. Μόνο για ανάγνωση [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Ανάγνωση [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. Ανάγνωση **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον προορισμό του γονικού υπερσυνδέσμου όταν υπάρχει. Ανάγνωση/εγγραφή [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Εάν το [Hyperlink](./) στοχεύει συγκεκριμένη διαφάνεια, επιστρέφει αυτή τη διαφάνεια. Μόνο για ανάγνωση [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συνδεδεμένη με το γονικό υπερσύνδεσμο. Ανάγνωση [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Λειτουργεί ως συνάρτηση κατακερματισμού για έναν συγκεκριμένο τύπο, κατάλληλη για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως πίνακας κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | Δημιουργεί μια παρουσία υπερσυνδέσμου. |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Δημιουργεί μια παρουσία υπερσυνδέσμου που δείχνει σε συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να ανατεθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, αλλιώς ο σύνδεσμος θα αποθηκευτεί ως NoAction. |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | Δημιουργεί μια παρουσία υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, παρακάμπτοντας δευτερογενείς ιδιότητες. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
| [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγραφής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Σύγκριση αναφοράς αντικειμένου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | Αναπαριστά την προέλευση του χρώματος του υπερσυνδέσμου - είτε στυλ είτε μορφή τμήματος. Εγγραφή [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | Καθορίζει εάν ο υπερσύνδεσμος πρέπει να επισημαίνεται κατά το κλικ. Εγγραφή **bool**. |
| void [set_History](./set_history/)(**bool**) override | Καθορίζει εάν ο προορισμός του γονικού υπερσυνδέσμου θα προστεθεί σε λίστα προβαλλόμενων υπερσυνδέσμων όταν κληθεί. Εγγραφή **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Αναπαριστά τον ήχο αναπαραγωγής του υπερσυνδέσμου. Εγγραφή [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | Καθορίζει εάν ο ήχος πρέπει να σταματήσει κατά το κλικ στον υπερσύνδεσμο. Εγγραφή **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | Επιστρέφει το πλαίσιο μέσα στο γονικό HTML frameset για τον προορισμό του γονικού υπερσυνδέσμου όταν υπάρχει. Ανάγνωση/εγγραφή [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | Επιστρέφει τη συμβολοσειρά που μπορεί να εμφανιστεί σε διεπαφή χρήστη ως συνδεδεμένη με το γονικό υπερσύνδεσμο. Εγγραφή [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτήρες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτήρες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτήρες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δεικτήρες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IHyperlink](../ihyperlink/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)