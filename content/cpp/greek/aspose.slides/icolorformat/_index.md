---
title: IColorFormat
second_title: Aspose.Slides για C++ API Reference
description: Αναπαριστά ένα χρώμα που χρησιμοποιείται σε μια παρουσίαση.
type: docs
weight: 1691
url: /el/aspose.slides/icolorformat/
---
## IColorFormat κλάση

Represents a color used in a presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Αντιγράφει τη μορφή χρώματος από το "color". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας την C# [Object.Equals](../../system/object/equals/) σημασιολογία. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς με το στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής με το στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| virtual **uint8_t** [get_B](./get_b/)() | Επιστρέφει το μπλε συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις μετατροπές χρώματος εφαρμοσμένες). Ορίζει χρώματα RGB και καθαρίζει όλες τις μετατροπές χρώματος. Διαβάζει [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Επιστρέφει τη λειτουργία μετατροπής χρώματος που εφαρμόζεται στο χρώμα στο συγκεκριμένο δείκτη. Ανάγνωση/εγγραφή [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Επιστρέφει τη συλλογή των μετατροπών χρώματος που εφαρμόζονται σε ένα χρώμα. Μόνο για ανάγνωση [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Επιστρέφει τη μέθοδο ορισμού χρώματος. Διαβάζει [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Επιστρέφει το μπλε συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Επιστρέφει το πράσινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Επιστρέφει το κόκκινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Επιστρέφει το πράσινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Επιστρέφει το συστατικό απόχρωσης ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Επιστρέφει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Επιστρέφει την προεπιλογή χρώματος. Διαβάζει [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Επιστρέφει το κόκκινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Επιστρέφει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Διαβάζει **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Επιστρέφει το χρώμα που προσδιορίζεται από ένα σχέδιο χρωμάτων. Διαβάζει [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Επιστρέφει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων του συστήματος. Διαβάζει [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων του μετρητή αναφορών που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί την κατακερματοποίηση προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκλάσεων. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά-τιμή αντικειμένου τύπου με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρο αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Ορίζει το μπλε συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Επιστρέφει το αποτέλεσμα χρώματος (με όλες τις μετατροπές χρώματος εφαρμοσμένες). Ορίζει χρώματα RGB και καθαρίζει όλες τις μετατροπές χρώματος. Γράφει [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Ορίζει τη λειτουργία μετατροπής χρώματος που εφαρμόζεται στο χρώμα στο συγκεκριμένο δείκτη. Ανάγνωση/εγγραφή [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Ορίζει τη μέθοδο ορισμού χρώματος. Γράφει [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Ορίζει το μπλε συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Ορίζει το πράσινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Ορίζει το κόκκινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Ορίζει το πράσινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Ορίζει το συστατικό απόχρωσης ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Ορίζει το συστατικό φωτεινότητας ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Ορίζει την προεπιλογή χρώματος. Γράφει [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Ορίζει το κόκκινο συστατικό ενός χρώματος. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Ορίζει το συστατικό κορεσμού ενός χρώματος στην αναπαράσταση HSL. Όλες οι μετατροπές χρώματος αγνοούνται. Γράφει **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Ορίζει το χρώμα που προσδιορίζεται από ένα σχέδιο χρωμάτων. Γράφει [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Ορίζει το χρώμα που προσδιορίζεται από τον πίνακα χρωμάτων του συστήματος. Γράφει [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδυνατινσθή δείκτη (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδυνατινστική κατάσταση. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμετρου αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρο αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρο αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Επιστρέφει ένα [System::String](../../system/string/) που αντιπροσωπεύει την τρέχουσα μορφή χρώματος. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει το κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδυνατινσθέντα μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδυνατινσθέντα μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IFillParamSource](../ifillparamsource/)
* Χώρος ονομάτων [Aspose::Slides](../)
* Βιβλιοθήκη [Aspose.Slides](../../)