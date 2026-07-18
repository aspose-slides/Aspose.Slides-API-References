---
title: ColorFormat
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
type: docs
weight: 339
url: /el/aspose.slides/colorformat/
---
## ColorFormat κλάση

Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Αντιγράφει τη μορφή χρώματος από \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Ελέγχει την ισότητα με το καθορισμένο αντικείμενο. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει την σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει την σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| **uint8_t** [get_B](./get_b/)() override | Επιστρέφει το μπλε συστατικό ενός χρώματος. Όλες οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Επιστρέφει το αποτέλεσμα χρώματος (με όλους τους μετασχηματισμούς χρώματος εφαρμοσμένους). Ορίζει τα χρώματα RGB και αφαιρεί όλους τους μετασχηματισμούς χρώματος. Διαβάστε [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Επιστρέφει τη λειτουργία μετασχηματισμού χρώματος που εφαρμόζεται στο χρώμα στον καθορισμένο δείκτη. Ανάγνωση/εγγραφή [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Επιστρέφει τη συλλογή των μετασχηματισμών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο ανάγνωση [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Επιστρέφει τη μέθοδο καθορισμού χρώματος. Διαβάστε [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Επιστρέφει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Επιστρέφει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Επιστρέφει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| **uint8_t** [get_G](./get_g/)() override | Επιστρέφει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. |
| **float** [get_Hue](./get_hue/)() override | Επιστρέφει το συστατικό απόχρωσης (hue) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Επιστρέφει το συστατικό φωτεινότητας (luminance) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο ανάγνωση [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Επιστρέφει τον γονέα [IPresentationComponent](../ipresentationcomponent/). Μόνο ανάγνωση [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Επιστρέφει το προεπιλεγμένο χρώμα. Διαβάστε [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Επιστρέφει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Επιστρέφει το συστατικό κορεσμού (saturation) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Διαβάστε **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Επιστρέφει το χρώμα που προσδιορίζεται από ένα χρωματικό σχήμα. Διαβάστε [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Επιστρέφει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων του συστήματος. Διαβάστε [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση του string και του nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση των strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστων αναφορών κατά την καθορισμένη τιμή. |
| void [set_B](./set_b/)(**uint8_t**) override | Ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Επιστρέφει το αποτέλεσμα χρώματος (με όλους τους μετασχηματισμούς χρώματος εφαρμοσμένους). Ορίζει τα χρώματα RGB και αφαιρεί όλους τους μετασχηματισμούς χρώματος. Εγγραφή [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Ορίζει τη λειτουργία μετασχηματισμού χρώματος που εφαρμόζεται στο χρώμα στον καθορισμένο δείκτη. Ανάγνωση/εγγραφή [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Ορίζει τη μέθοδο καθορισμού χρώματος. Εγγραφή [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Ορίζει το μπλε συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Ορίζει το πράσινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. |
| void [set_Hue](./set_hue/)(**float**) override | Ορίζει το συστατικό απόχρωσης (hue) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Ορίζει το συστατικό φωτεινότητας (luminance) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Ορίζει το προεπιλεγμένο χρώμα. Εγγραφή [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Ορίζει το κόκκινο συστατικό ενός χρώματος. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Ορίζει το συστατικό κορεσμού (saturation) ενός χρώματος σε αναπαράσταση HSL. Όλοι οι μετασχηματισμοί χρώματος αγνοούνται. Εγγραφή **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Ορίζει το χρώμα που προσδιορίζεται από ένα χρωματικό σχήμα. Εγγραφή [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων του συστήματος. Εγγραφή [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή των δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστων αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστων αναφορών. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Επιστρέφει ένα [System::String](../../system/string/) που αντιπροσωπεύει την τρέχουσα μορφή χρώματος. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί για αυτό, χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [PVIObject](../pviobject/)
* Κλάση [IColorFormat](../icolorformat/)
* Ονομαχώρος [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)