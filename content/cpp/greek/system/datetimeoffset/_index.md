---
title: DateTimeOffset
second_title: Aspose.Slides για C++ API Αναφορά
description: "Περιέχει την ημερομηνία και την ώρα της ημέρας σε σχέση με το Συγχρονισμένο Παγκόσμιο Χρόνο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση System::MakeObject(). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκύψουν σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα να εγκλείετε αυτήν την κλάση σε δείκτη System::SmartPtr και να χρησιμοποιείτε αυτόν τον δείκτη για να το περάσετε σε λειτουργίες ως όρισμα."
type: docs
weight: 235
url: /el/system/datetimeoffset/
---
## DateTimeOffset κλάση

Περιέχει την ημερομηνία και την ώρα της ημέρας σχετικά με το Συντονισμένο Παγκόσμιο Χρόνο. Τα αντικείμενα αυτής της κλάσης πρέπει να εκχωρούνται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../makeobject/). Ποτέ μην δημιουργείτε παρουσία αυτού του τύπου στην στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα προκαλέσει σφάλματα χρόνου εκτέλεσης και/ή σφάλματα δήλωσης. Πάντα να εγκλείετε αυτήν την κλάση σε δείκτη [System::SmartPtr](../smartptr/) και να χρησιμοποιείτε αυτόν τον δείκτη για να το περάσετε σε λειτουργίες ως όρισμα.

```cpp
class DateTimeOffset
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Προσθέτει ένα καθορισμένο χρονικό διάστημα στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Προσθέτει έναν καθορισμένο αριθμό ημερών στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Προσθέτει έναν καθορισμένο αριθμό ωρών στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Προσθέτει έναν καθορισμένο αριθμό χιλιοστών δευτερολέπτων στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Προσθέτει έναν καθορισμένο αριθμό λεπτών στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Προσθέτει έναν καθορισμένο αριθμό μηνών στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Προσθέτει έναν καθορισμένο αριθμό δευτερολέπτων στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Προσθέτει έναν καθορισμένο αριθμό ticks στο αντικείμενο [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Προσθέτει έναν καθορισμένο αριθμό ετών στο αντικείμενο [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Συγκρίνει δύο αντικείμενα [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Συγκρίνει δύο αντικείμενα [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Συγκρίνει δύο αντικείμενα [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Προεπιλεγμένος κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Κατασκευαστής. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Κατασκευαστής. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Ελέγχει αν δύο αντικείμενα [DateTimeOffset](./) αντιπροσωπεύουν το ίδιο χρονικό σημείο. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Ελέγχει αν δύο αντικείμενα [DateTimeOffset](./) αντιπροσωπεύουν το ίδιο χρονικό σημείο. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ελέγχει αν δύο αντικείμενα [DateTimeOffset](./) αντιπροσωπεύουν το ίδιο χρονικό σημείο. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Ελέγχει αν δύο αντικείμενα [DateTimeOffset](./) αντιπροσωπεύουν το ίδιο χρονικό σημείο και έχουν το ίδιο offset. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ελέγχει αν δύο αντικείμενα [DateTimeOffset](./) αντιπροσωπεύουν το ίδιο χρονικό σημείο και έχουν το ίδιο offset. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) αρχείο χρόνου σε ημερομηνία και ώρα με τοπικό offset χρόνου. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time σε αντικείμενο [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time σε αντικείμενο [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Λαμβάνει το στοιχείο ημερομηνίας του τρέχοντος αντικειμένου. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Λαμβάνει την τιμή [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Λαμβάνει την ημέρα του μήνα του τρέχοντος αντικειμένου. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Λαμβάνει την ημέρα της εβδομάδας του τρέχοντος αντικειμένου. |
| int [get_DayOfYear](./get_dayofyear/)() const | Λαμβάνει τη μέρα του έτους του τρέχοντος αντικειμένου. |
| int [get_Hour](./get_hour/)() const | Λαμβάνει το στοιχείο ώρας του τρέχοντος αντικειμένου. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Λαμβάνει την τιμή [DateTime](../datetime/) που αντιπροσωπεύει την τοπική ημερομηνία και ώρα. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Λαμβάνει το στοιχείο χιλιοστών δευτερολέπτου του τρέχοντος αντικειμένου. |
| int [get_Minute](./get_minute/)() const | Λαμβάνει το στοιχείο λεπτού του τρέχοντος αντικειμένου. |
| int [get_Month](./get_month/)() const | Λαμβάνει το στοιχείο μήνα του τρέχοντος αντικειμένου. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Λαμβάνει το [DateTimeOffset](./) του οποίου η ημερομηνία και ώρα ορίζονται στην τρέχουσα τοπική ώρα και του οποίου το offset ορίζεται στο offset της τοπικής ώρας. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Λαμβάνει το offset από UTC. |
| constexpr int [get_Second](./get_second/)() const | Λαμβάνει το στοιχείο δευτερολέπτου του τρέχοντος αντικειμένου. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Λαμβάνει τον αριθμό των ticks του τρέχοντος αντικειμένου. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Λαμβάνει την ώρα της ημέρας του τρέχοντος αντικειμένου. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Λαμβάνει την τιμή [DateTime](../datetime/) που αντιπροσωπεύει την ημερομηνία και ώρα UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Λαμβάνει το [DateTimeOffset](./) του οποίου η ημερομηνία και ώρα ορίζονται στην τρέχουσα ώρα UTC και του οποίου το offset είναι [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Λαμβάνει τον αριθμό των ticks του τρέχοντος αντικειμένου σε ώρα UTC. |
| int [get_Year](./get_year/)() const | Λαμβάνει το στοιχείο έτους του τρέχοντος αντικειμένου. |
| int [GetHashCode](./gethashcode/)() const | Λαμβάνει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [DateTimeOffset](./). |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο και το συγκεκριμένο αντικείμενο [DateTimeOffset](./) αντιπροσωπεύουν διαφορετικές τιμές ημερομηνίας και ώρας. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTimeOffset](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι το άθροισμα της τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο και του συγκεκριμένου χρονικού διαστήματος. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Επιστρέφει μια νέα παρουσία της κλάσης [DateTimeOffset](./) που αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι το αποτέλεσμα της αφαίρεσης του συγκεκριμένου χρονικού διαστήματος από την τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Επιστρέφει μια παρουσία της κλάσης [TimeSpan](../timespan/) που αντιπροσωπεύει το χρονικό διάστημα μεταξύ των τιμών ημερομηνίας και ώρας που αντιπροσωπεύονται από το τρέχον και το συγκεκριμένο αντικείμενο. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι νωρίτερη από την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [DateTimeOffset](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι νωρίτερα ή ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [DateTimeOffset](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο και το συγκεκριμένο αντικείμενο [DateTimeOffset](./) αντιπροσωπεύουν την ίδια τιμή ημερομηνίας και ώρας. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι μεταγενέστερη από την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [DateTimeOffset](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Καθορίζει αν το τρέχον αντικείμενο αντιπροσωπεύει την τιμή ημερομηνίας και ώρας που είναι μεταγενέστερη ή ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [DateTimeOffset](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει το συγκεκριμένο string σε ισοδύναμο [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τον καθορισμένο παροχέα μορφοποίησης και το στυλ μορφοποίησης. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τη συγκεκριμένη μορφή, παροχέα μορφοποίησης και στυλ μορφοποίησης. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Μετατρέπει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τις συγκεκριμένες μορφές, παροχέα μορφοποίησης και στυλ μορφοποίησης. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Αφαιρεί ένα καθορισμένο χρονικό διάστημα από το τρέχον αντικείμενο. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Αφαιρέτει μια καθορισμένη τιμή [DateTimeOffset](./) από το τρέχον αντικείμενο. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Μετατρέπει το τρέχον αντικείμενο σε αρχείο χρόνου [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Μετατρέπει το τρέχον αντικείμενο σε αντικείμενο που αντιπροσωπεύει την τοπική ώρα. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Αντικαθιστά το offset του τρέχοντος αντικειμένου με το καθορισμένο offset. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη συγκεκριμένη μορφή και παροχέα μορφοποίησης. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τον καθορισμένο παροχέα μορφοποίησης. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τη συγκεκριμένη μορφή. |
| [String](../string/) [ToString](./tostring/)() const | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Μετατρέπει το τρέχον αντικείμενο σε αντικείμενο που αντιπροσωπεύει τον χρόνο UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Λαμβάνει τα χιλιοστά του δευτερολέπτου που έχουν περάσει από την αρχή της εποχής Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Λαμβάνει τα δευτερόλεπτα που έχουν περάσει από την αρχή της εποχής Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Προσπαθεί να μετατρέψει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Προσπαθεί να μετατρέψει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τον καθορισμένο παροχέα μορφοποίησης και το στυλ μορφοποίησης. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Προσπαθεί να μετατρέψει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τις συγκεκριμένες μορφές, παροχέα μορφοποίησης και στυλ μορφοποίησης. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Προσπαθεί να μετατρέψει το συγκεκριμένο string σε αντικείμενο [DateTimeOffset](./) χρησιμοποιώντας τη συγκεκριμένη μορφή, παροχέα μορφοποίησης και στυλ μορφοποίησης. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει ένα αντικείμενο [TypeInfo](../typeinfo/) που αντιπροσωπεύει τη δομή [TimeSpan](../timespan/). |

## Πεδία

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Λαμβάνει το μέγιστο offset σε ticks. |
| static [MaxValue](./maxvalue/) | Λαμβάνει τη μεγαλύτερη τιμή [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Λαμβάνει το ελάχιστο offset σε ticks. |
| static [MinValue](./minvalue/) | Λαμβάνει την πιο πρώιμη τιμή [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Λαμβάνει την αρχή της εποχής Unix. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)