---
title: NumberFormatInfo
second_title: Aspose.Slides για C++ - Αναφορά API
description: "Περιέχει πληροφορίες σχετικά με το πώς να μορφοποιούνται οι αριθμοί. Οι λειτουργίες ορισμού είναι ενεργοποιημένες μόνο σε αντικείμενα που δεν είναι μόνο για ανάγνωση. Τα αντικείμενα αυτής της κατηγορίας πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε εμφανίσεις αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κατηγορία σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 248
url: /el/system.globalization/numberformatinfo/
---
## NumberFormatInfo κατηγορία

Περιέχει πληροφορίες σχετικά με το πώς να μορφοποιούνται οι αριθμοί. Οι λειτουργίες ρύθμισης είναι ενεργές μόνο σε αντικείμενα που δεν είναι μόνο για ανάγνωση. Τα αντικείμενα αυτής της κατηγορίας πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε εμφανίσεις αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assert. Πάντα τυλίξτε αυτήν την κατηγορία σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν το δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Κλωνοποιεί τις πληροφορίες μορφοποίησης. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρ'όλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερικούς σκοπούς. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Λαμβάνει τον αριθμό των δεκαδικών ψηφίων του νομίσματος. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Λαμβάνει το διαχωριστικό δεκαδικών του νομίσματος. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Λαμβάνει το διαχωριστικό ομάδας του νομίσματος. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Λαμβάνει τον αριθμό των δεκαδικών ψηφίων ανά ομάδα για το νόμισμα. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Λαμβάνει το πρότυπο αρνητικού νομίσματος. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Λαμβάνει το πρότυπο θετικού νομίσματος. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Λαμβάνει το σύμβολο νομίσματος. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Λαμβάνει τις πληροφορίες μορφοποίησης αριθμών που ορίζονται από την τρέχουσα κουλτούρα του νήματος. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Λαμβάνει μια τιμή που καθορίζει πώς να εμφανίζεται το σχήμα ενός ψηφίου. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Λαμβάνει τις πληροφορίες μορφοποίησης αριθμών που ορίζονται από την αμετάβλητη κουλτούρα. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Ελέγχει αν η μορφή είναι μόνο για ανάγνωση. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Λαμβάνει το σύμβολο Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Λαμβάνει τα σύμβολα ψηφίων (0 έως 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Λαμβάνει το σύμβολο αρνητικού άπειρου. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Λαμβάνει το αρνητικό πρόσημο. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Λαμβάνει τον αριθμό των δεκαδικών ψηφίων. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Λαμβάνει το διαχωριστικό δεκαδικών. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Λαμβάνει το διαχωριστικό ομάδας αριθμών. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Λαμβάνει τον αριθμό των ψηφίων ανά ομάδα. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Λαμβάνει το πρότυπο αρνητικού αριθμού. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Λαμβάνει τον αριθμό των δεκαδικών θέσεων στις τιμές ποσοστών. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Λαμβάνει το διαχωριστικό δεκαδικών στις τιμές ποσοστών. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Λαμβάνει το διαχωριστικό ομάδας στις τιμές ποσοστών. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Λαμβάνει τον αριθμό των ψηφίων ανά ομάδα τιμών ποσοστών. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Λαμβάνει το πρότυπο αρνητικού ποσοστού. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Λαμβάνει το πρότυπο θετικού ποσοστού. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Λαμβάνει το σύμβολο ποσοστού. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Λαμβάνει το σύμβολο permille. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Λαμβάνει το σύμβολο θετικού άπειρου. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Λαμβάνει το θετικό πρόσημο. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Λαμβάνει διαμορφωτή συγκεκριμένου τύπου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash προσαρμοσμένων αντικειμένων. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Λαμβάνει το διαμορφωτή που συσχετίζεται με τον παροχέα μορφοποίησης. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [NumberFormatInfo](./numberformatinfo/)() | Κατασκευής προεπιλογής (αμετάβλητο [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευής αντιγραφής. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποκλάσεων με αντιγραφή. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστέος ανάθεσης. Δεν αντιγράφει τίποτα, πραγματικά, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την κατασκευή υποκλάσεων με αντιγραφή. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Λαμβάνει την έκδοση μόνο για ανάγνωση του διαμορφωτή. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Ορίζει τον αριθμό των δεκαδικών ψηφίων του νομίσματος. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό δεκαδικών του νομίσματος. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό ομάδας του νομίσματος. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ορίζει τον αριθμό των δεκαδικών ψηφίων ανά ομάδα για το νόμισμα. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Ορίζει το πρότυπο αρνητικού νομίσματος. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Ορίζει το πρότυπο θετικού νομίσματος. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο νομίσματος. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Ορίζει μια τιμή που καθορίζει πώς να εμφανίζεται το σχήμα ενός ψηφίου. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα σύμβολα ψηφίων (0 έως 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο αρνητικού άπειρου. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Ορίζει το αρνητικό πρόσημο. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ορίζει τον αριθμό των δεκαδικών ψηφίων. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό δεκαδικών. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό ομάδας αριθμών. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ορίζει τον αριθμό των ψηφίων ανά ομάδα. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Ορίζει το πρότυπο αρνητικού αριθμού. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Ορίζει τον αριθμό των δεκαδικών θέσεων στις τιμές ποσοστών. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό δεκαδικών στις τιμές ποσοστών. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό ομάδας στις τιμές ποσοστών. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Ορίζει τον αριθμό των ψηφίων ανά ομάδα τιμής ποσοστού. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Ορίζει το πρότυπο αρνητικού ποσοστού. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Ορίζει το πρότυπο θετικού ποσοστού. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο ποσοστού. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο permille. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο θετικού άπειρου. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Ορίζει το θετικό πρόσημο. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το ν' όρισμα προτύπου ως αδύναμο δείκτη (**uint32_t**) (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κλήεται απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κλήεται απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απερίαση της δήλωσης C# lock(). Κλήση άμεσα ή χρήση αντικειμένου επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κλήεται απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κλήεται απευθείας· αντί γι' αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κατηγορία [Object](../../system/object/)
* Κατηγορία [IFormatProvider](../../system/iformatprovider/)
* Κατηγορία [ICloneable](../../system/icloneable/)
* Ονομαχώρος [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)