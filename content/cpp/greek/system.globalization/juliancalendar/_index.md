---
title: JulianCalendar
second_title: Aspose.Slides για την τεκμηρίωση API του C++
description: "Ιουλιανό ημερολόγιο. Αντικείμενα αυτής της κλάσης πρέπει να κατανεμηθούν μόνο χρησιμοποιώντας τη λειτουργία System::MakeObject() συνάρτηση. Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτή την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να το περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 209
url: /el/system.globalization/juliancalendar/
---
## JulianCalendar κλάση

Ιουλιανό ημερολόγιο. Αντικείμενα αυτής της κλάσης πρέπει να κατανεμητούν μόνο χρησιμοποιώντας τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα assertion. Πάντα τυλίξτε αυτή την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για τη μεταφορά του σε συναρτήσεις ως όρισμα.

```cpp
class JulianCalendar : public System::Globalization::Calendar
```

## Methods

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Προσθέτει ημέρες σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Προσθέτει ώρες σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Προσθέτει χιλιοστά του δευτερολέπτου σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Προσθέτει λεπτά σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Προσθέτει μήνες σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Προσθέτει δευτερόλεπτα σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Προσθέτει εβδομάδες σε σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Προσθέτει χρόνια σε σημείο χρόνου. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Πληροφορίες RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει έναν κοινό δείκτη προς αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Ανακτά τον τύπο αλγορίθμου. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Ανακτά το δείκτη της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Ανακτά την τιμή της τρέχουσας εποχής. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Ανακτά λίστα εποχών που υπάρχουν στο ημερολόγιο. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει αν το ημερολόγιο είναι μόνο για ανάγνωση. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Μέγιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ελάχιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Ανακτά το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ανακτά τη δομή δεδομένων του μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Ανακτά την ημέρα του μήνα για το καθορισμένο σημείο χρόνου. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Ανακτά την ημέρα της εβδομάδας για το καθορισμένο σημείο χρόνου. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Ανακτά την ημέρα του χρόνου για το καθορισμένο σημείο χρόνου. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Ανακτά τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Ανακτά τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Ανακτά τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Ανακτά τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Ανακτά τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Ανακτά τον αριθμό ημερών σε συγκεκριμένο έτος. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Ανακτά την εποχή για το καθορισμένο σημείο χρόνου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Διευκολύνει το hash προσαρμοσμένων αντικειμένων. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Ανακτά τις ώρες για το καθορισμένο σημείο χρόνου. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Ανακτά το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Ανακτά το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Ανακτά το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Ανακτά τα χιλιοστά του δευτερολέπτου για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Ανακτά τα λεπτά για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Ανακτά το μήνα για το καθορισμένο σημείο χρόνου. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Ανακτά τον αριθμό μηνών στο καθορισμένο έτος. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Πληροφορίες RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Πληροφορίες RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Ανακτά τα δευτερόλεπτα για το καθορισμένο σημείο χρόνου. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ανακτά τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Ανακτά την εβδομάδα του έτους για το καθορισμένο σημείο χρόνου. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Ανακτά το έτος για το καθορισμένο σημείο χρόνου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια περίπτωση του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ελέγχει αν ο μήνας είναι δίσεκτος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ελέγχει αν ο μήνας είναι δίσεκτος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ελέγχει αν ο μήνας είναι δίσεκτος. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τις τιμές έτους, μήνα, ημέρας και εποχής. |
|  [JulianCalendar](./juliancalendar/)() | Κατασκευαστής. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκατηγοριών. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή αντιγράφων υποκατηγοριών. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Ανακτά την έκδοση μόνο για ανάγνωση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ανακτά την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Δημιουργεί αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Δημιουργεί αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε 4-ψήφιο έτος χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκεύασμα C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την απελευθέρωση του statement lock() της C#. Καλείται απευθείας ή χρησιμοποιήστε το αντικείμενο sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Fields

| Field | Description |
| --- | --- |
| static constexpr [JulianEra](./julianera/) | Τρέχουσα ιουλιανή εποχή. |

## Δείτε επίσης

* Κλάση [Calendar](../calendar/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)