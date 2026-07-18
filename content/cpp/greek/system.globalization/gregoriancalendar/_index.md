---
title: GregorianCalendar
second_title: Aspose.Slides για C++ API Αναφορά
description: "Γρηγοριανό ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject() function. Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο stack ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα εκτέλεσης και/ή σφάλματα αστοχίας. Πάντα τυλίξτε αυτήν την κλάση με δείκτη System::SmartPtr pointer και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε ως όρισμα σε συναρτήσεις."
type: docs
weight: 131
url: /el/system.globalization/gregoriancalendar/
---
## GregorianCalendar κλάση

Gregorian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Προσθέτει ημέρες στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Προσθέτει ώρες στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Προσθέτει χιλιοστά του δευτερολέπτου στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Προσθέτει λεπτά στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Προσθέτει μήνες στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Προσθέτει δευτερόλεπτα στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Προσθέτει εβδομάδες στο σημείο χρόνου. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Προσθέτει έτη στο σημείο χρόνου. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Πληροφορίες RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει έναν shared pointer σε αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Λαμβάνει τον τύπο αλγορίθμου. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | Λαμβάνει τύπο ημερολογίου Gregorian. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Λαμβάνει δείκτη της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Λαμβάνει τιμή της τρέχουσας εποχής. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Λαμβάνει λίστα των εποχών που υπάρχουν στο ημερολόγιο. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει αν το ημερολόγιο είναι μόνο για ανάγνωση. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Μέγιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ελάχιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Λαμβάνει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα του μήνα για το συγκεκριμένο χρονικό σημείο. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα της εβδομάδας για το συγκεκριμένο χρονικό σημείο. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα του έτους για το συγκεκριμένο χρονικό σημείο. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο μήνα. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Λαμβάνει τον αριθμό των ημερών σε συγκεκριμένο έτος. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | Λαμβάνει την προεπιλεγμένη παρουσία ημερολογίου Gregorian. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την εποχή για το συγκεκριμένο χρονικό σημείο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Λαμβάνει τις ώρες για το συγκεκριμένο χρονικό σημείο. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Λαμβάνει το δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Λαμβάνει το δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Λαμβάνει το δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Λαμβάνει χιλιοστά του δευτερολέπτου για το συγκεκριμένο χρονικό σημείο. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Λαμβάνει λεπτά για το συγκεκριμένο χρονικό σημείο. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Λαμβάνει τον μήνα για το συγκεκριμένο χρονικό σημείο. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Λαμβάνει τον αριθμό των μηνών στο συγκεκριμένο έτος. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Πληροφορίες RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Πληροφορίες RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Λαμβάνει δευτερόλεπτα για το συγκεκριμένο χρονικό σημείο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογία της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει την εβδομάδα του έτους για το συγκεκριμένο χρονικό σημείο. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Λαμβάνει το έτος για το συγκεκριμένο χρονικό σημείο. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Δομεί συγκεκριμένο ημερολόγιο Gregorian. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογία του τελεστή C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ελέγχει εάν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ελέγχει εάν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ελέγχει εάν η ημέρα είναι δίσεκτη. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ελέγχει εάν ο μήνας είναι δίσεκτος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ελέγχει εάν ο μήνας είναι δίσεκτος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ελέγχει εάν ο μήνας είναι δίσεκτος. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ελέγχει εάν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ελέγχει εάν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ελέγχει εάν το έτος είναι δίσεκτο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τιμές έτους, μήνα, ημέρας και εποχής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την αντιγραφή προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευάστης αντιγράφου. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-παραγώγων μέσω αντιγραφής. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Κατασκευάστης ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή κλάσεων-παραγώγων μέσω αντιγραφής. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Λαμβάνει την έκδοση μόνο για ανάγνωση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει με αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την ορισμένη τιμή. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Ορίζει τον τύπο ημερολογίου Gregorian. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά του. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά του. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά του. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε τετραψήφιο χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί τον κατασκευαστή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται άμεσα ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να καλείται απευθείας· αντίθετα, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [ADEra](./adera/) | Τρέχουσα εποχή. |

## Δείτε επίσης

* Κλάση [Calendar](../calendar/)
* Χώρος ονομάτων [System::Globalization](../)
* Library [Aspose.Slides](../../)