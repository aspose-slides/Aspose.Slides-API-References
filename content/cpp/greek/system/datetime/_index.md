---
title: DateTime
second_title: Aspose.Slides για C++ API Αναφορά
description: "Αντιπροσωπεύει μια συγκεκριμένη τιμή ημερομηνίας και ώρας στην χρονική συνεχή. Αυτός ο τύπος πρέπει να κατανεμηθεί στο στοίβα και να περάσει σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 222
url: /el/system/datetime/
---
## DateTime κλάση

Αντιπροσωπεύει μια συγκεκριμένη τιμή ημερομηνίας και ώρας στην χρονική συνέχειά της. Αυτός ο τύπος πρέπει να κατανεμηθεί στο στοίβα και να περνιέται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class DateTime
```

## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που προκύπτει από την προσθήκη του καθορισμένου χρονικού διαστήματος στην τιμή ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού ημερών. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού ωρών. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού χιλιοστών του δευτερολέπτου. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού λεπτών. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού μηνών. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού δευτερολέπτων. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας η οποία είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου αριθμού διαστημάτων 100-νανοδευτερολέπτου. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Επιστρέφει ένα νέο αντικείμενο της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ίση με αυτή του τρέχοντος αντικειμένου με το στοιχείο του έτους αυξημένο κατά τον καθορισμένο αριθμό. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Συγκρίνει δύο τιμές που αντιπροσωπεύονται από τις καθορισμένες παρουσίες της κλάσης [DateTime](./) και επιστρέφει την τιμή που υποδεικνύει τη σχετική θέση των τιμών στην χρονογραμμή. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Συγκρίνει δύο τιμές ημερομηνίας και ώρας που αντιπροσωπεύονται από το τρέχον αντικείμενο και την καθορισμένη παρουσία της κλάσης [DateTime](./) και επιστρέφει την τιμή που υποδεικνύει τη σχετική θέση των τιμών στην χρονογραμμή. |
| constexpr [DateTime](./datetime/)() | Δημιουργεί μια παρουσία που αντιπροσωπεύει την ελάχιστη δυνατή τιμή ημερομηνίας και ώρας ίση με MinValue. |
| [DateTime](./datetime/)(int, int, int) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα και ημέρα. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα και ημέρα στο καθορισμένο ημερολογιακό σύστημα. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα, ημέρα, ώρα, λεπτό και δευτερόλεπτο. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα, ημέρα, ώρα, λεπτό και δευτερόλεπτο. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα, ημέρα, ώρα, λεπτό και δευτερόλεπτο στο καθορισμένο ημερολογιακό σύστημα. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα, ημέρα, ώρα, λεπτό, δευτερόλεπτο και χιλιοστό του δευτερολέπτου. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από συγκεκριμένο έτος, μήνα, ημέρα, ώρα, λεπτό, δευτερόλεπτο και χιλιοστό του δευτερολέπτου στο καθορισμένο ημερολογιακό σύστημα. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από αριθμό ticks. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Δημιουργεί μια παρουσία που αντιπροσωπεύει μια τιμή ημερομηνίας και ώρας που ορίζεται από αριθμό ticks. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | Αντιγράφει μια παρουσία. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Επιστρέφει τον αριθμό ημερών στο καθορισμένο μήνα του καθορισμένου έτους. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Καθορίζει αν οι καθορισμένες παρουσίες της κλάσης [DateTime](./) αντιπροσωπεύουν την ίδια τιμή ημερομηνίας και ώρας. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Καθορίζει αν η καθορισμένη παρουσία της κλάσης [DateTime](./) αντιπροσωπεύει την ίδια τιμή ημερομηνίας και ώρας με το τρέχον αντικείμενο. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Αποσειριοποιεί την τιμή ημερομηνίας και ώρας από το καθορισμένο μη-αρνητικό 64-bit ακέραιο και θέτει τη νέα παρουσία της κλάσης [DateTime](./) σε αυτήν την τιμή. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Μετατρέπει το καθορισμένο File time σε μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την ίδια τιμή ημερομηνίας και ώρας ως τοπική ώρα. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Μετατρέπει το καθορισμένο File time σε μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την ίδια τιμή ημερομηνίας και ώρας ως UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Επιστρέφει μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας ισοδύναμη με το καθορισμένο OLE Automation Date. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Μετατρέπει το καθορισμένο Unix time σε μια παρουσία της κλάσης [DateTime](./). ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει το μέρος ημερομηνίας της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο, με όλα τα στοιχεία του μέρους ώρας να είναι 0. |
| int [get_Day](./get_day/)() const | Επιστρέφει τον σειρά αριθμό της ημέρας στον μήνα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Επιστρέφει μια τιμή που αντιπροσωπεύει την ημέρα της εβδομάδας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| int [get_DayOfYear](./get_dayofyear/)() const | Επιστρέφει τον σειρά αριθμό της ημέρας στο έτος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr int [get_Hour](./get_hour/)() const | Επιστρέφει το στοιχείο της ώρας της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Επιστρέφει μια τιμή που δηλώνει αν η ημερομηνία και ώρα του τρέχοντος αντικειμένου είναι τοπική, UTC ή καμία από τις δύο. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Επιστρέφει το στοιχείο των χιλιοστών του δευτερολέπτου της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr int [get_Minute](./get_minute/)() const | Επιστρέφει το στοιχείο του λεπτού της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| int [get_Month](./get_month/)() const | Επιστρέφει τον σειρά αριθμό του μήνα στο έτος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [DateTime](./) [get_Now](./get_now/)() | Επιστρέφει μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τρέχουσα ώρα ως τοπική ώρα. |
| constexpr int [get_Second](./get_second/)() const | Επιστρέφει το στοιχείο του δευτερολέπτου της τιμής ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Επιστρέφει τον αριθμό των διαστημάτων 100-νανοδευτερολέπτου που έχουν παρέλθει από 0:00:00 UTC, 1 Ιανουαρίου 0001, στο Γρηγοριανό ημερολόγιο, έως την τιμή ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Επιστρέφει την τιμή που αντιπροσωπεύει το χρονικό διάστημα από την αρχή της ημέρας που αντιπροσωπεύεται από το τρέχον αντικείμενο μέχρι την τιμή ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| static [DateTime](./) [get_Today](./get_today/)() | Επιστρέφει μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τρέχουσα ημερομηνία με όλα τα στοιχεία του τμήματος ώρας του αντικειμένου να είναι 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Επιστρέφει μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τρέχουσα ώρα ως UTC. |
| int [get_Year](./get_year/)() const | Επιστρέφει το έτος που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Λαμβάνει τα μέρη της ημερομηνίας. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Επιστρέφει έναν πίνακα συμβόλων όπου κάθε στοιχείο είναι η συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου μορφοποιημένη με έναν από τους τυπικούς μορφοποιητές ημερομηνίας και ώρας. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Επιστρέφει έναν πίνακα συμβόλων όπου κάθε στοιχείο είναι η συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου μορφοποιημένη με τον καθορισμένο τυπικό μορφοποιητή ημερομηνίας και ώρας. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Επιστρέφει έναν πίνακα συμβόλων όπου κάθε στοιχείο είναι η συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου μορφοποιημένη με έναν από τους τυπικούς μορφοποιητές ημερομηνίας και ώρας και με τον καθορισμένο πάροχο μορφοποίησης. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Επιστρέφει έναν πίνακα συμβόρων όπου κάθε στοιχείο είναι η συμβολοσειρά αναπαράστασης του τρέχοντος αντικειμένου μορφοποιημένη με τον καθορισμένο τυπικό μορφοποιητή ημερομηνίας και ώρας και με τον πάροχο μορφοποίησης. |
| int [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Καθορίζει αν η τιμή ημερομηνίας και ώρας που αντιπροσωπεύεται από το τρέχον αντικείμενο εμπίπτει στο εύρος της θερινής ώρας για τη τρέχουσα χρονική ζώνη. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Καθορίζει αν το καθορισμένο έτος είναι δίσεκτο. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο και το καθορισμένο αντικείμενο [DateTime](./) αντιπροσωπεύουν διαφορετικές τιμές ημερομηνίας και ώρας. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου χρονικού διαστήματος. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Ορίζει το τρέχον αντικείμενο στην τιμή ημερομηνίας και ώρας που είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του καθορισμένου χρονικού διαστήματος. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που προκύπτει από την αφαίρεση του καθορισμένου χρονικού διαστήματος από την τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Επιστρέφει μια παρουσία της κλάσης [TimeSpan](../timespan/) που αντιπροσωπεύει το χρονικό διάστημα μεταξύ των τιμών ημερομηνίας και ώρας που αντιπροσωπεύονται από τα τρέχοντα και τα καθορισμένα αντικείμενα. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Ορίζει το τρέχον αντικείμενο στην τιμή ημερομηνίας και ώρας που προκύπτει από την αφαίρεση του καθορισμένου χρονικού διαστήματος από την τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι νωρίτερη από την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [DateTime](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι νωρίτερη ή ίση με την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [DateTime](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Αναθέτει την τιμή που αντιπροσωπεύεται από την καθορισμένη παρουσία [DateTime](./) στο τρέχον αντικείμενο. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο και το καθορισμένο αντικείμενο [DateTime](./) αντιπροσωπεύουν την ίδια τιμή ημερομηνίας και ώρας. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι μεταγενέστερη από την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [DateTime](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι μεταγενέστερη ή ίση με την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [DateTime](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./). |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας μορφοποίηση ειδική για πολιτισμό. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας το καθορισμένο φορμάτ και πληροφορίες μορφοποίησης ειδικές για πολιτισμό. Η μορφή της συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο φορμάτ. Εναίρει εξαίρεση εάν η μετατροπή αποτύχει. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας τα καθορισμένα φορμάτ, πληροφορίες μορφοποίησης ειδικές για πολιτισμό και στυλ. Η μορφή της συμβολοσειράς πρέπει να ταιριάζει ακριβώς με ένα ή περισσότερα από τα καθορισμένα φορμάτ. Εναίρει εξαίρεση εάν η μετατροπή αποτύχει. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Δημιουργεί ένα νέο αντικείμενο [DateTime](./) που αντιπροσωπεύει τον ίδιο αριθμό ticks με το καθορισμένο αντικείμενο [DateTime](./) και αντιπροσωπεύει τοπική ώρα, UTC ή καμία, όπως καθορίζεται από το όρισμα **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που προκύπτει από την αφαίρεση του καθορισμένου χρονικού διαστήματος από την τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Επιστρέφει μια παρουσία της κλάσης [TimeSpan](../timespan/) που αντιπροσωπεύει το χρονικό διάστημα μεταξύ των τιμών ημερομηνίας και ώρας που αντιπροσωπεύονται από τα τρέχοντα και τα καθορισμένα αντικείμενα. |
| **int64_t** [ToBinary](./tobinary/)() const | Σειριοποιεί το τρέχον αντικείμενο. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Επιστρέφει μια τιμή που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου ως File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Μετατρέπει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου σε File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου ως τοπική ώρα. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Επιστρέφει μια συμβολοσειρά που περιέχει την εκφώνηση της ημερομηνίας σε μορφή πλήρους ημερομηνίας του τρέχοντος αντικειμένου. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Επιστρέφει μια συμβολοσειρά που περιέχει την εκφώνηση της ώρας σε μορφή πλήρους ώρας του τρέχοντος αντικειμένου. |
| **double** [ToOADate](./tooadate/)() const | Επιστρέφει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου ως OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Επιστρέφει μια συμβολοσειρά που περιέχει την εκφώνηση της ημερομηνίας σε μορφή σύντομης ημερομηνίας του τρέχοντος αντικειμένου. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Επιστρέφει μια συμβολοσειρά που περιέχει την εκφώνηση της ώρας σε μορφή σύντομης ώρας του τρέχοντος αντικειμένου. |
| [String](../string/) [ToString](./tostring/)() const | Επιστρέφει τη συμβολοσειρά που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου χρησιμοποιώντας τις συμβάσεις μορφοποίησης που ορίζονται από την τρέχουσα πολιτισμική ρύθμιση. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου χρησιμοποιώντας τον καθορισμένο μορφότυπο και τις συμβάσεις μορφοποίησης που ορίζονται από την τρέχουσα πολιτισμική ρύθμιση. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου ως UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Επιστρέφει μια τιμή που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας του τρέχοντος αντικειμένου ως Unix time. ΓΙΑ ΕΣΩΤΕΡΙΚΗ ΧΡΗΣΗ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας τις καθορισμένες πληροφορίες μορφοποίησης ειδικές για πολιτισμό και στυλ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας το καθορισμένο φορμάτ, πληροφορίες μορφοποίησης ειδικές για πολιτισμό και στυλ. Η μορφή της συμβολοσειράς πρέπει να ταιριάζει ακριβώς με το καθορισμένο φορμάτ. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Μετατρέπει τη καθορισμένη συμβολοσειρά που αναπαριστά μια τιμή ημερομηνίας και ώρας στην ισοδύναμη παρουσία [DateTime](./) χρησιμοποιώντας τα καθορισμένα φορμάτ, πληροφορίες μορφοποίησης ειδικές για πολιτισμό και στυλ. Η μορφή της συμβολοσειράς πρέπει να ταιριάζει ακριβώς με ένα ή περισσότερα από τα καθορισμένα φορμάτ. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει ένα αντικείμενο [TypeInfo](../typeinfo/) που περιέχει πληροφορίες σχετικά με αυτήν την κλάση. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Ο αριθμός των 100-νανοδευτερολέπτων στο χρονικό διάστημα μεταξύ της ελάχιστης δυνατής και της μέγιστης δυνατής τιμής [DateTime](./). |
| static [MaxValue](./maxvalue/) | Μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει τη μέγιστη δυνατή τιμή ημερομηνίας και ώρας. |
| static constexpr [MinTicks](./minticks/) | Ο ελάχιστος αριθμός ticks που μπορεί να αντιπροσωπεύσει μια παρουσία της κλάσης [DateTime](./). |
| static [MinValue](./minvalue/) | Μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει τη ελάχιστη δυνατή τιμή ημερομηνίας και ώρας. |
| static constexpr [TicksPerDay](./ticksperday/) | Ο αριθμός των ticks σε μια ημέρα. |
| static constexpr [TicksPerHour](./ticksperhour/) | Ο αριθμός των ticks σε μια ώρα. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Ο αριθμός των ticks σε μια μικροδευτερόλεπτο. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Ο αριθμός των ticks σε ένα χιλιοστό του δευτερολέπτου. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Ο αριθμός των ticks σε ένα λεπτό. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Ο αριθμός των ticks σε ένα δευτερόλεπτο. |
| static [UnixEpoch](./unixepoch/) | Μια παρουσία της κλάσης [DateTime](./) που αντιπροσωπεύει την αρχή της εποχής Unix (01.01.1970 00:00:00). |

## Παρατηρήσεις

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Δημιουργεί μια παρουσία της κλάσης 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Εκτυπώνει την παρουσία σε πολλές μορφές.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)