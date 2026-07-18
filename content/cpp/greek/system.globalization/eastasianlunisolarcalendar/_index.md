---
title: EastAsianLunisolarCalendar
second_title: Αναφορά API Aspose.Slides για C++
description: "Ασιατικό ηλιακό-σεληνιακό ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο με τη λειτουργία System::MakeObject() συνάρτηση. Ποτέ μην δημιουργείτε ένα αντίτυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα περικλείετε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιείτε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 105
url: /el/system.globalization/eastasianlunisolarcalendar/
---
## EastAsianLunisolarCalendar κλάση

Ανατολικό σεληνοηλιακό ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο με τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε αντικείμενο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας το τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή αποτυχίες ελέγχου. Πάντα να ενσωματώνετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα.

```cpp
class EastAsianLunisolarCalendar : public System::Globalization::Calendar
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
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Προσθέτει έτη σε σημείο χρόνου. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Πληροφορίες RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Δημιουργεί αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει ένα κοινόχρηστο δείκτη σε αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Πληροφορίες RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Λαμβάνει το ευρετήριο της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Λαμβάνει την τιμή της τρέχουσας εποχής. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](../calendar/get_eras/)() const | Λαμβάνει τη λίστα των εποχών που υπάρχουν στο ημερολόγιο. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](../calendar/get_id/)() const | Λαμβάνει το αναγνωριστικό του ημερολογίου. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει αν το ημερολόγιο είναι μόνο για ανάγνωση. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](../calendar/get_maxsupporteddatetime/)() const | Μέγιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](../calendar/get_minsupporteddatetime/)() const | Ελάχιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Λαμβάνει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| int [GetCelestialStem](./getcelestialstem/)(int) const | Λαμβάνει το ουράνιο στελέχος. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα του μήνα για το καθορισμένο σημείο χρόνου. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα της εβδομάδας για το καθορισμένο σημείο χρόνου. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα του έτους για το καθορισμένο σημείο χρόνου. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Λαμβάνει την εποχή για το καθορισμένο σημείο χρόνου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία κατακερματισμού προσαρμοσμένων αντικειμένων. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Λαμβάνει τις ώρες για το καθορισμένο σημείο χρόνου. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int) const | Λαμβάνει το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](../calendar/getleapmonth/)(int, int) const | Λαμβάνει το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Λαμβάνει χιλιοστά του δευτερολέπτου για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Λαμβάνει λεπτά για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Λαμβάνει τον μήνα για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Λαμβάνει τον αριθμό μηνών στο καθορισμένο έτος. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Λαμβάνει τον αριθμό μηνών στο καθορισμένο έτος. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Λαμβάνει δευτερόλεπτα για το καθορισμένο σημείο χρόνου. |
| virtual int [GetSexagenaryYear](./getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει το έτος στον εξαδικό κύκλο. |
| int [GetTerrestrialBranch](./getterrestrialbranch/)(int) const | Λαμβάνει τον γήινο κλάδο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει την εβδομάδα του έτους για το καθορισμένο σημείο χρόνου. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει το έτος για το καθορισμένο σημείο χρόνου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από το targetType. Αναλογικό του τελεστή C# 'is'. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](../calendar/isleapday/)(int, int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ελέγχει αν ο μήνας είναι δίστυχος. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ελέγχει αν ο μήνας είναι δίστυχος. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](../calendar/isleapyear/)(int, int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τις τιμές έτους, μήνα, ημέρας και εποχής. |
| void [Lock](../../system/object/lock/)() | Εφαρμόζει την κλείδωση δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγράφου. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών με αντιγραφή. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Καταχωρητής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών με αντιγραφή. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Λαμβάνει την έκδοση μόνο για ανάγνωση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αντικείμενο τύπου τιμής με την αναφορά προς nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Δημιουργεί αντικείμενο [DateTime](../../system/datetime/) από τα στοιχεία. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Δημιουργεί αντικείμενο [DateTime](../../system/datetime/) από τα στοιχεία. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε 4ψήφιο έτος χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Εφαρμόζει την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Εφαρμόζει την απελευθέρωση της δήλωσης C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· αντί αυτής, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Calendar](../calendar/)
* Ονομαχώρος [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)