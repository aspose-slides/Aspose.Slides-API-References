---
title: JapaneseCalendar
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ιαπωνικό ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στο στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα περιβάλλετε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 183
url: /el/system.globalization/japanesecalendar/
---
## Κλάση JapaneseCalendar

Ιαπωνικό ημερολόγιο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο με τη λειτουργία [System::MakeObject()](../../system/makeobject/). Ποτέ μην δημιουργείτε μια παρουσία αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα περιβάλλετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τον περάσετε ως όρισμα σε συναρτήσεις.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Προσθέτει ημέρες σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Προσθέτει ώρες σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Προσθέτει χιλιοστά του δευτερολέπτου σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Προσθέτει λεπτά σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Προσθέτει μήνες σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Προσθέτει δευτερόλεπτα σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Προσθέτει εβδομάδες σε χρονική στιγμή. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Προσθέτει έτη σε χρονική στιγμή. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Πληροφορίες RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει έναν κοινό δείκτη σε αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Παίρνει τον τύπο αλγορίθμου. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Παίρνει το δείκτη της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Παίρνει την τιμή της τρέχουσας εποχής. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Παίρνει τη λίστα των εποχών που υπάρχουν στο ημερολόγιο. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει εάν το ημερολόγιο είναι μόνο για ανάγνωση. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Μέγιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ελάχιστο χρονικό σημείο που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Παίρνει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Παίρνει τη δομή δεδομένων μετρητή αναφοράς που συνδέεται με το αντικείμενο. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Παίρνει την ημέρα του μήνα για το καθορισμένο χρονικό σημείο. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Παίρνει την ημέρα της εβδομάδας για το καθορισμένο χρονικό σημείο. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Παίρνει την ημέρα του χρόνου για το καθορισμένο χρονικό σημείο. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Παίρνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Παίρνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Παίρνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Παίρνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Παίρνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Παίρνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Παίρνει την εποχή για το καθορισμένο χρονικό σημείο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογία της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί τη δημιουργία hash για προσαρμοσμένα αντικείμενα. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Παίρνει τις ώρες για το καθορισμένο χρονικό σημείο. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Παίρνει τον δίσεγχο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Παίρνει τον δίσεγχο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Παίρνει τον δίσεγχο μήνα για το καθορισμένο έτος. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Παίρνει τα χιλιοστά του δευτερολέπτου για το καθορισμένο χρονικό σημείο. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Παίρνει τα λεπτά για το καθορισμένο χρονικό σημείο. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Παίρνει το μήνα για το καθορισμένο χρονικό σημείο. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Παίρνει τον αριθμό μηνών στο συγκεκριμένο έτος. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Πληροφορίες RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Πληροφορίες RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Παίρνει τα δευτερόλεπτα για το καθορισμένο χρονικό σημείο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Παίρνει τον πραγματικό τύπο του αντικειμένου. Αναλογία κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Παίρνει την εβδομάδα του έτους για το καθορισμένο χρονικό σημείο. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Παίρνει το έτος για το καθορισμένο χρονικό σημείο. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια εμφάνιση του τύπου που περιγράφεται από το targetType. Αναλογία του τελεστή C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ελέγχει εάν η ημέρα είναι δίσημη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ελέγχει εάν η ημέρα είναι δίσημη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ελέγχει εάν η ημέρα είναι δίσημη. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Ελέγχει εάν ο μήνας είναι δίσημος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Ελέγχει εάν ο μήνας είναι δίσημος. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Ελέγχει εάν ο μήνας είναι δίσημος. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ελέγχει εάν το έτος είναι δίσημο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ελέγχει εάν το έτος είναι δίσημο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ελέγχει εάν το έτος είναι δίσημο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τις τιμές έτους, μήνα, ημέρας και εποχής. |
|  [JapaneseCalendar](./japanesecalendar/)() | Κατασκευαστής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement κλειδώματος C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογία της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγορίων. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Παίρνει την έκδοση μόνο για ανάγνωση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα με βάση την αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορικά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόμετρη αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει τη μετατροπή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Παίρνει την τρέχουσα τιμή του κοινόμετρου αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρη αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρη αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Δομεί το αντικείμενο [DateTime](../../system/datetime/) από τα συστατικά. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε τετραψήφιο έτος χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογία της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί την απελευθέρωση του statement κλειδώματος C# lock(). Κλήση απευθείας ή χρήση του αντικειμένου φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Αποδεσμεύει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Calendar](../calendar/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)