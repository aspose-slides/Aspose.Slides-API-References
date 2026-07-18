---
title: DateTimeFormatInfo
second_title: Aspose.Slides για C++ – Αναφορά API
description: "Σύνολο παραμέτρων μορφοποίησης ημερομηνίας και ώρας. Τα αντικείμενα αυτής της κλάσης πρέπει να δημιουργούνται μόνο με τη λειτουργία System::MakeObject() . Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στο stack ή με τον τελεστή new, καθώς αυτό θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ανάθεσης. Πάντοτε τυλίξτε αυτήν την κλάση σε δείκτη System::SmartPtr και χρησιμοποιήστε αυτόν τον δείκτη για να τη περάσετε στις συναρτήσεις ως όρισμα."
type: docs
weight: 66
url: /el/system.globalization/datetimeformatinfo/
---
## DateTimeFormatInfo κλάση

Set of date and time formatting parameters. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DateTimeFormatInfo : public virtual System::Object,
                           public System::IFormatProvider,
                           public System::ICloneable
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Κλωνοποιεί τις πληροφορίες μορφότυπου. |
|  [DateTimeFormatInfo](./datetimeformatinfo/)() | Κατασκευαστής προεπιλογής, δημιουργεί αμετάβλητες πληροφορίες μορφότυπου. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση σημείου κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, ακόμη και αν σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedDayNames](./get_abbreviateddaynames/)() const | Λαμβάνει τα συντομευμένα ονόματα των ημερών. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthGenitiveNames](./get_abbreviatedmonthgenitivenames/)() const | Λαμβάνει τα συντομευμένα ονόματα των μηνών σε γενική μορφή. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AbbreviatedMonthNames](./get_abbreviatedmonthnames/)() const | Λαμβάνει τα συντομευμένα ονόματα των μηνών. |
| [String](../../system/string/) [get_AMDesignator](./get_amdesignator/)() const | Λαμβάνει το σύμβολο ΠΜ. |
| [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\> [get_Calendar](./get_calendar/)() const | Λαμβάνει το ημερολόγιο που σχετίζεται με το formatter. |
| [CalendarWeekRule](../calendarweekrule/) [get_CalendarWeekRule](./get_calendarweekrule/)() const | Λαμβάνει τον κανόνα εβδομάδας ημερολογίου που σχετίζεται με το formatter. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Λαμβάνει το formatteur ημερομηνίας και ώρας του τρέχοντος νήματος. |
| [String](../../system/string/) [get_DateSeparator](./get_dateseparator/)() const | Λαμβάνει το διαχωριστικό ημερομηνίας. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_DayNames](./get_daynames/)() const | Λαμβάνει τα ονόματα των ημερών. |
| [DayOfWeek](../../system/dayofweek/) [get_FirstDayOfWeek](./get_firstdayofweek/)() const | Λαμβάνει την πρώτη ημέρα της εβδομάδας. |
| [String](../../system/string/) [get_FullDateTimePattern](./get_fulldatetimepattern/)() const | Λαμβάνει το πλήρες πρότυπο ημερομηνίας και ώρας. |
| static const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Λαμβάνει το αμετάβλητο formatteur ημερομηνίας και ώρας. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Ελέγχει εάν το formatter είναι μόνο για ανάγνωση. |
| [String](../../system/string/) [get_LongDatePattern](./get_longdatepattern/)() const | Λαμβάνει το μακρύ πρότυπο ημερομηνίας. |
| [String](../../system/string/) [get_LongTimePattern](./get_longtimepattern/)() const | Λαμβάνει το μακρύ πρότυπο ώρας. |
| [String](../../system/string/) [get_MonthDayPattern](./get_monthdaypattern/)() const | Λαμβάνει το πρότυπο ημέρας μήνα. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthGenitiveNames](./get_monthgenitivenames/)() const | Λαμβάνει τα ονόματα των μηνών σε γενική μορφή. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_MonthNames](./get_monthnames/)() const | Λαμβάνει τα ονόματα των μηνών. |
| [String](../../system/string/) [get_NativeCalendarName](./get_nativecalendarname/)() const | Λαμβάνει το εγγενές όνομα ημερολογίου εάν είναι διαθέσιμο. |
| [String](../../system/string/) [get_PMDesignator](./get_pmdesignator/)() const | Λαμβάνει το σύμβολο ΜΜ. |
| [String](../../system/string/) [get_RFC1123Pattern](./get_rfc1123pattern/)() const | Λαμβάνει το πρότυπο RFC1123. |
| [String](../../system/string/) [get_ShortDatePattern](./get_shortdatepattern/)() const | Λαμβάνει το σύντομο πρότυπο ημερομηνίας. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_ShortestDayNames](./get_shortestdaynames/)() const | Λαμβάνει τα πιο σύντομα δυνατά ονόματα ημερών. |
| [String](../../system/string/) [get_ShortTimePattern](./get_shorttimepattern/)() const | Λαμβάνει το σύντομο πρότυπο ώρας. |
| [String](../../system/string/) [get_SortableDateTimePattern](./get_sortabledatetimepattern/)() const | Λαμβάνει το ταξινομήσιμο πρότυπο ημερομηνίας και ώρας. |
| [String](../../system/string/) [get_TimeSeparator](./get_timeseparator/)() const | Λαμβάνει το διαχωριστικό ώρας. |
| [String](../../system/string/) [get_UniversalSortableDateTimePattern](./get_universalsortabledatetimepattern/)() const | Λαμβάνει το καθολικό ταξινομήσιμο πρότυπο ημερομηνίας και ώρας. |
| [String](../../system/string/) [get_YearMonthPattern](./get_yearmonthpattern/)() const | Λαμβάνει το πρότυπο έτους και μήνα. |
| [String](../../system/string/) [GetAbbreviatedDayName](./getabbreviateddayname/)([DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει το συντομευμένο όνομα ημέρας της εβδομάδας. |
| [String](../../system/string/) [GetAbbreviatedEraName](./getabbreviatederaname/)(int) const | Λαμβάνει το συντομευμένο όνομα εποχής. |
| [String](../../system/string/) [GetAbbreviatedMonthName](./getabbreviatedmonthname/)(int) const | Λαμβάνει το συντομευμένο όνομα μήνα. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)() const | Λαμβάνει όλα τα πρότυπα στα οποία μπορούν να μορφοποιηθούν τιμές ημερομηνίας και ώρας. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetAllDateTimePatterns](./getalldatetimepatterns/)(char16_t) const | Λαμβάνει όλα τα πρότυπα στα οποία μπορούν να μορφοποιηθούν τιμές ημερομηνίας και ώρας χρησιμοποιώντας τη συγκεκριμένη συμβολοσειρά μορφοποίησης. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| [String](../../system/string/) [GetDayName](./getdayname/)([DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει το όνομα ημέρας της εβδομάδας. |
| int [GetEra](./getera/)(const [String](../../system/string/)\&) const | Λαμβάνει την εποχή με βάση το όνομα. |
| [String](../../system/string/) [GetEraName](./geteraname/)(int) const | Λαμβάνει το όνομα εποχής. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Λαμβάνει το formatteur συγκεκριμένου τύπου. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογικό της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Λαμβάνει το formatteur που σχετίζεται με τον πάροχο μορφότυπου. |
| [String](../../system/string/) [GetLeapYearMonthName](./getleapyearmonthname/)(int) const | Λαμβάνει το όνομα του μήνα σε δίσεχινο έτος. |
| [String](../../system/string/) [GetMonthGenitiveName](./getmonthgenitivename/)(int) const | Λαμβάνει το γενικό όνομα του μήνα. |
| [String](../../system/string/) [GetMonthName](./getmonthname/)(int) const | Λαμβάνει το όνομα του μήνα. |
| [String](../../system/string/) [GetShortestDayName](./getshortestdayname/)([DayOfWeek](../../system/dayofweek/)) const | Λαμβάνει το πιο σύντομο όνομα για την καθορισμένη ημέρα της εβδομάδας. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογικό της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει ένα στιγμιότυπο του τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογικό της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάσεων μέσω copy construction. |
| [DateTimeFormatInfo](./)\& [operator=](./operator_equal/)(const [DateTimeFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκλάσεων μέσω copy construction. |
| static [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [ReadOnly](./readonly/)(const [DateTimeFormatInfoPtr](../datetimeformatinfoptr/)\&) | Λαμβάνει τη μόνο για ανάγνωση έκδοση του formatter. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει κατά αναφορά αντικείμενο τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρά και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδική περίπτωση του [Object::ReferenceEquals](../../system/object/referenceequals/) για συμβολοσειρές. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον κοινόχρηστο μετρητή αναφοράς κατά την καθορισμένη τιμή. |
| void [set_AbbreviatedDayNames](./set_abbreviateddaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα συντομευμένα ονόματα των ημερών. |
| void [set_AbbreviatedMonthGenitiveNames](./set_abbreviatedmonthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα συντομευμένα ονόματα των μηνών σε γενική μορφή. |
| void [set_AbbreviatedMonthNames](./set_abbreviatedmonthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα συντομευμένα ονόματα των μηνών. |
| void [set_AMDesignator](./set_amdesignator/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο ΠΜ. |
| void [set_Calendar](./set_calendar/)(const [SharedPtr](../../system/sharedptr/)\<[Calendar](../calendar/)\>\&) | Ορίζει το ημερολόγιο που σχετίζεται με το formatter. |
| void [set_CalendarWeekRule](./set_calendarweekrule/)([CalendarWeekRule](../calendarweekrule/)) | Ορίζει τον κανόνα εβδομάδας ημερολογίου που σχετίζεται με το formatter. |
| void [set_DateSeparator](./set_dateseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό ημερομηνίας. |
| void [set_DayNames](./set_daynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα ονόματα των ημερών. |
| void [set_FirstDayOfWeek](./set_firstdayofweek/)([DayOfWeek](../../system/dayofweek/)) | Ορίζει την πρώτη ημέρα της εβδομάδας. |
| void [set_FullDateTimePattern](./set_fulldatetimepattern/)(const [String](../../system/string/)\&) | Ορίζει το πλήρες πρότυπο ημερομηνίας και ώρας. |
| void [set_LongDatePattern](./set_longdatepattern/)(const [String](../../system/string/)\&) | Ορίζει το μακρύ πρότυπο ημερομηνίας. |
| void [set_LongTimePattern](./set_longtimepattern/)(const [String](../../system/string/)\&) | Ορίζει το μακρύ πρότυπο ώρας. |
| void [set_MonthDayPattern](./set_monthdaypattern/)(const [String](../../system/string/)\&) | Ορίζει το πρότυπο ημέρας μήνα. |
| void [set_MonthGenitiveNames](./set_monthgenitivenames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα ονόματα μηνών σε γενική μορφή. |
| void [set_MonthNames](./set_monthnames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα ονόματα των μηνών. |
| void [set_PMDesignator](./set_pmdesignator/)(const [String](../../system/string/)\&) | Ορίζει το σύμβολο ΜΜ. |
| void [set_ShortDatePattern](./set_shortdatepattern/)(const [String](../../system/string/)\&) | Ορίζει το σύντομο πρότυπο ημερομηνίας. |
| void [set_ShortestDayNames](./set_shortestdaynames/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Ορίζει τα πιο σύντομα δυνατά ονόματα ημερών. |
| void [set_ShortTimePattern](./set_shorttimepattern/)(const [String](../../system/string/)\&) | Ορίζει το σύντομο πρότυπο ώρας. |
| void [set_TimeSeparator](./set_timeseparator/)(const [String](../../system/string/)\&) | Ορίζει το διαχωριστικό ώρας. |
| void [set_YearMonthPattern](./set_yearmonthpattern/)(const [String](../../system/string/)\&) | Ορίζει το πρότυπο έτους και μήνα. |
| void [SetAllDateTimePatterns](./setalldatetimepatterns/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, char16_t) | Ορίζει τα πρότυπα για τη συγκεκριμένη μορφή. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n-οστό όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινόχρηστο). Επιτρέπει την αλλαγή δεικτών σε δομές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του κοινόχρηστου μετρητή αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον κοινόχρηστο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον κοινόχρησητο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογικό της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλέστε άμεσα ή χρησιμοποιήστε το αντικείμενο [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί άμεσα· χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Κλάση [IFormatProvider](../../system/iformatprovider/)
* Κλάση [ICloneable](../../system/icloneable/)
* Χώρος ονομάτων [System::Globalization](../)
* Βιβλιοθήκη [Aspose.Slides](../../)