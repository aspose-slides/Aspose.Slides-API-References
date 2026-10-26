---
title: ThaiBuddhistCalendar
second_title: Aspose.Slides για C++ API Αναφορά
description: "Thai Buddhist ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε εμφάνισμα αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 378
url: /el/system.globalization/thaibuddhistcalendar/
---
## ThaiBuddhistCalendar κλάση


Thai Buddhist calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ThaiBuddhistCalendar : public System::Globalization::Calendar
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει έναν shared pointer σε αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Λαμβάνει τον τύπο αλγορίθμου. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Λαμβάνει το δείκτη της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Λαμβάνει την τιμή της τρέχουσας εποχής. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Λαμβάνει τη λίστα των εποχών που υπάρχουν στο ημερολόγιο. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει αν το ημερολόγιο είναι μόνο για ανάγνωση. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Μέγιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ελάχιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Λαμβάνει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα του μήνα για το συγκεκριμένο σημείο χρόνου. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα της εβδομάδας για το συγκεκριμένο σημείο χρόνου. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την ημέρα του έτους για το συγκεκριμένο σημείο χρόνου. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Λαμβάνει την εποχή για το συγκεκριμένο σημείο χρόνου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αντίστοιχο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Λαμβάνει τις ώρες για το συγκεκριμένο σημείο χρόνου. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Λαμβάνει τον δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Λαμβάνει τον δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Λαμβάνει τον δίσεκτο μήνα για το συγκεκριμένο έτος. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Λαμβάνει χιλιοστά του δευτερολέπτου για το συγκεκριμένο σημείο χρόνου. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Λαμβάνει τα λεπτά για το συγκεκριμένο σημείο χρόνου. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Λαμβάνει τον μήνα για το συγκεκριμένο σημείο χρόνου. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Λαμβάνει τον αριθμό των μηνών στο συγκεκριμένο έτος. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Πληροφορίες RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Πληροφορίες RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Λαμβάνει τα δευτερόλεπτα για το συγκεκριμένο σημείο χρόνου. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αντίστοιχο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει την εβδομάδα του έτους για το συγκεκριμένο σημείο χρόνου. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Λαμβάνει το έτος για το συγκεκριμένο σημείο χρόνου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αντίστοιχο του τελεστή C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ελέγχει αν ο μήνας είναι δίσεκος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ελέγχει αν ο μήνας είναι δίσεκος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ελέγχει αν ο μήνας είναι δίσεκος. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τιμές έτους, μήνα, ημέρας και εποχής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί την εντολή κλειδώματος C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αντίστοιχο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή των υποκατηγοριών. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής εκχώρησης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και ενεργοποιεί την αντιγραφή των υποκατηγοριών. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Λαμβάνει την έκδοση μόνο για ανάγνωση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική υλοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για τη περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή shared reference κατά την καθορισμένη τιμή. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμη αναφορά (αντί για shared). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή shared reference. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή shared reference. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε smart pointers ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή shared reference. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε smart pointers ή ThisProtector. |
|  [ThaiBuddhistCalendar](./thaibuddhistcalendar/)() | Κατασκευαστής. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Κατασκευάζει το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Κατασκευάζει το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Κατασκευάζει το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε 4-ψηφίο έτος χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αντίστοιχο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την έκφραση C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της εντολής C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε smart pointers ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε smart pointers ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [ThaiBuddhistEra](./thaibuddhistera/) | Τρέχουσα εποχή Thai Buddhist. |
## Δείτε επίσης

* Κλάση [Calendar](../calendar/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)