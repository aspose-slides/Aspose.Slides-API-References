---
title: KoreanLunisolarCalendar
second_title: Aspose.Slides για C++ API Αναφορά
description: "Κορεάτικό ηλιακό-σεληνιακό ημερολόγιο. Δεν έχει υλοποιηθεί. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργήσετε αντίτυπο αυτού του τύπου στη στοίβα ή με τον τελεστή new, καθώς αυτό θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ασυμφωνίας. Πάντα να τυλίγετε αυτή την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν τον δείκτη για να τη μεταβιβάζετε σε συναρτήσεις ως όρισμα."
type: docs
weight: 235
url: /el/system.globalization/koreanlunisolarcalendar/
---
## KoreanLunisolarCalendar κλάση

Korean lunisolar calendar. Not implemented. Objects of this κλάση should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this κλάση into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class KoreanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου και επιστρέφει έναν κοινό δείκτη σε αυτό. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με οποιαδήποτε τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | Πληροφορίες RTTI. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Λαμβάνει τον δείκτη της τρέχουσας εποχής. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Λαμβάνει την τιμή της τρέχουσας εποχής. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Λαμβάνει τη λίστα των εποχών που υπάρχουν στο ημερολόγιο. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Ελέγχει αν το ημερολόγιο είναι μόνο για ανάγνωση. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Μέγιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Ελάχιστο σημείο χρόνου που υποστηρίζεται από το ημερολόγιο. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Λαμβάνει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Λαμβάνει το ουράνιο στέλεχος. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα του μήνα για το καθορισμένο σημείο χρόνου. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα της εβδομάδας για το καθορισμένο σημείο χρόνου. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει την ημέρα του έτους για το καθορισμένο σημείο χρόνου. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο μήνα. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Λαμβάνει τον αριθμό ημερών σε συγκεκριμένο έτος. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Λαμβάνει την εποχή για το καθορισμένο σημείο χρόνου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το κατακερματισμό προσαρμοσμένων αντικειμένων. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Λαμβάνει τις ώρες για το καθορισμένο σημείο χρόνου. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Λαμβάνει το δίσεκτο μήνα για το καθορισμένο έτος. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Πληροφορίες RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Πληροφορίες RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Λαμβάνει χιλιοστά του δευτερολέπτου για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Λαμβάνει λεπτά για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Λαμβάνει το μήνα για το καθορισμένο σημείο χρόνου. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Λαμβάνει τον αριθμό μηνών στο καθορισμένο έτος. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Λαμβάνει τον αριθμό μηνών στο καθορισμένο έτος. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Λαμβάνει δευτερόλεπτα για το καθορισμένο σημείο χρόνου. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει το έτος στον εξάηκο βρόχο. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Λαμβάνει την επίγεια κλάδο. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει την εβδομάδα του έτους για το καθορισμένο σημείο χρόνου. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Λαμβάνει το έτος για το καθορισμένο σημείο χρόνου. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Ελέγχει αν η ημέρα είναι δίσεκτη. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Ελέγχει αν ο μήνας είναι δίσεκτος. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Ελέγχει αν ο μήνας είναι δίσεκτος. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Ελέγχει αν το έτος είναι δίσεκτο. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Ελέγχει τιμές έτους, μήνα, ημέρας και εποχής. |
|  [KoreanLunisolarCalendar](./koreanlunisolarcalendar/)() | Κατασκευαστής. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δε αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Καταχώρηση τελεστή. Δε αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει την κατασκευή υποκατηγοριών μέσω αντιγραφής. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Λαμβάνει τη μόνο για ανάγνωση έκδοση του ημερολογίου. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση string και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για περίπτωση strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινό μετρητή αναφορών κατά την καθορισμένη τιμή. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Ορίζει το τελευταίο έτος που μπορεί να αναπαρασταθεί με 2 ψηφία. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα πρότυπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την εναλλαγή δεικτών σε δοχεία σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόμετρητή αναφορών. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόμετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόμετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Δημιουργεί [DateTime](../../system/datetime/) αντικείμενο από τα συστατικά. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Δημιουργεί [DateTime](../../system/datetime/) αντικείμενο από τα συστατικά. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Μετατρέπει το έτος σε έτος 4 ψηφίων χρησιμοποιώντας την ιδιότητα TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί την κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε απευθείας ή χρησιμοποιήστε το αντικείμενο επιτήρησης [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφορών. Δεν θα πρέπει να κληθεί απευθείας· αντί για αυτό, χρησιμοποιήστε έξυπνους δεικτές ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [GregorianEra](./gregorianera/) | Τρέχουσα γρηγοριανή εποχή. |

## Δείτε επίσης

* Κλάση [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)