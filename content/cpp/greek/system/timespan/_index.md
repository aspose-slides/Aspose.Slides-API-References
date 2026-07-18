---
title: TimeSpan
second_title: Aspose.Slides για το C++ API Αναφορά
description: "Αναπαριστά ένα διάστημα χρόνου. Αυτός ο τύπος πρέπει να κατανεμηθεί στη στοίβα και να περάσει στις συναρτήσεις κατά τιμή ή κατά αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 1288
url: /el/system/timespan/
---
## TimeSpan κλάση


Αναπαριστά ένα διάστημα χρόνου. Αυτός ο τύπος πρέπει να κατανεμηθεί στη στοίβα και να περάσει σε συναρτήσεις κατά τιμή ή κατά αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class TimeSpan
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Επιστρέφει ένα νέο στιγμιότυπο της κλάσης [TimeSpan](./) που αντιπροσωπεύει ένα διάστημα χρόνου το οποίο είναι το άθροισμα των διαστημάτων χρόνου που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Συγκρίνει δύο αντικείμενα [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Συγκρίνει το τρέχον και το καθορισμένο αντικείμενα. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Συγκρίνει το τρέχον και το καθορισμένο αντικείμενα. |
| [TimeSpan](./) [Duration](./duration/)() const | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) του οποίου η τιμή είναι η απόλυτη τιμή του τρέχοντος αντικειμένου. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Επιστρέφει true εάν τα καθορισμένα αντικείμενα αντιπροσωπεύουν το ίδιο διάστημα χρόνου, διαφορετικά - false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Επιστρέφει ένα νέο αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα. |
| constexpr int [get_Days](./get_days/)() const | Επιστρέφει το στοιχείο ημερών του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr int [get_Hours](./get_hours/)() const | Επιστρέφει το στοιχείο ωρών του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Επιστρέφει το στοιχείο χιλιοστών του δευτερολέπτου του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr int [get_Minutes](./get_minutes/)() const | Επιστρέφει το στοιχείο λεπτών του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr int [get_Seconds](./get_seconds/)() const | Επιστρέφει το στοιχείο δευτερολέπτων του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Επιστρέφει τον αριθμό των διαστημάτων των 100 νανοδευτερολέπτων που αποτελούν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Επιστρέφει την τιμή του τρέχοντος αντικειμένου [TimeSpan](./) εκφρασμένη σε ολόκληρες και κλασματικές ημέρες. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Επιστρέφει την τιμή του τρέχοντος αντικειμένου [TimeSpan](./) εκφρασμένη σε ολόκληρες και κλασματικές ώρες. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Επιστρέφει την τιμή του τρέχοντος αντικειμένου [TimeSpan](./) εκφρασμένη σε ολόκληρα και κλασματικά χιλιοστά του δευτερολέπτου. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Επιστρέφει την τιμή του τρέχοντος αντικειμένου [TimeSpan](./) εκφρασμένη σε ολόκληρα και κλασματικά λεπτά. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Επιστρέφει την τιμή του τρέχοντος αντικειμένου [TimeSpan](./) εκφρασμένη σε ολόκληρα και κλασματικά δευτερόλεπτα. |
| int [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κώδικα κατακερματισμού για το τρέχον αντικείμενο. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Επιστρέφει ένα νέο στιγμιότυπο του αντικειμένου [TimeSpan](./) που αντιπροσωπεύει την αρνητική τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο δεν είναι ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Επιστρέφει ένα νέο στιγμιότυπο της κλάσης [TimeSpan](./) που αντιπροσωπεύει ένα διάστημα χρόνου το οποίο είναι το άθροισμα των διαστημάτων χρόνου που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Επιστρέφει τον εαυτό του. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Αποδίδει στο τρέχον αντικείμενο το διάστημα χρόνου που είναι το άθροισμα του διαστήματος που αντιπροσωπεύεται από το τρέχον και το καθορισμένο αντικείμενο. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Επιστρέφει ένα νέο στιγμιότυπο της κλάσης [TimeSpan](./) που αντιπροσωπεύει ένα διάστημα χρόνου το οποίο είναι το αποτέλεσμα αφαίρεσης του διαστήματος που αντιπροσωπεύεται από το καθορισμένο αντικείμενο από το διάστημα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Επιστρέφει ένα νέο στιγμιότυπο του αντικειμένου [TimeSpan](./) που αντιπροσωπεύει την αρνητική τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο [TimeSpan](./). |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Αποδίδει στο τρέχον αντικείμενο το διάστημα χρόνου που είναι το αποτέλεσμα αφαίρεσης του διαστήματος που αντιπροσωπεύεται από το καθορισμένο αντικείμενο από το διάστημα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερο από το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μικρότερο ή ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Ορίζει το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [TimeSpan](./) στο τρέχον αντικείμενο [TimeSpan](./). |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερο από το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Καθορίζει αν το διάστημα χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο είναι μεγαλύτερο ή ίσο με το διάστημα χρόνου που αντιπροσωπεύεται από το καθορισμένο αντικείμενο. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./). |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας τον καθορισμένο πάροχο μορφής. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας τα καθορισμένα φορμά, πάροχο μορφής και στυλ. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας το καθορισμένο φορμά, πάροχο μορφής και στυλ. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Επιστρέφει ένα νέο στιγμιότυπο της κλάσης [TimeSpan](./) που αντιπροσωπεύει ένα διάστημα χρόνου το οποίο είναι το αποτέλεσμα αφαίρεσης του διαστήματος που αντιπροσωπεύεται από το καθορισμένο αντικείμενο από το διάστημα που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| constexpr [TimeSpan](./timespan/)() | Κατασκευάζει ένα αντικείμενο [TimeSpan](./) που αντιπροσωπεύει ένα μηδενικό διάστημα χρόνου. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Κατασκευάζει μια εμφάνιση της κλάσης [TimeSpan](./) που αντιπροσωπεύει το καθορισμένο διάστημα χρόνου. |
|  [TimeSpan](./timespan/)(int, int, int) | Κατασκευάζει μια εμφάνιση της κλάσης [TimeSpan](./) που αντιπροσωπεύει το διάστημα χρόνου που ισούται με το άθροισμα των καθορισμένων ωρών, λεπτών και δευτερολέπτων. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Κατασκευάζει μια εμφάνιση της κλάσης [TimeSpan](./) που αντιπροσωπεύει το διάστημα χρόνου που ισούται με το άθροισμα των καθορισμένων ωρών, λεπτών, δευτερολέπτων και χιλιόσων του δευτερολέπτου. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Κατασκευάζει ένα αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το διάστημα χρόνου ίσο με το διάστημα που αντιπροσωπεύεται από το καθορισμένο αντικείμενο [TimeSpan](./). |
| [String](../string/) [ToString](./tostring/)() const | Επιστρέφει τη συμβολοσειρά αναπαράστασης του διαστήματος χρόνου που αντιπροσωπεύεται από το τρέχον αντικείμενο. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Μετατρέπει την τιμή του τρέχοντος αντικειμένου σε ισοδύναμη συμβολοσειρά, χρησιμοποιώντας το καθορισμένο φορμά. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Μετατρέπει την τιμή του τρέχοντος αντικειμένου σε ισοδύναμη συμβολοσειρά, χρησιμοποιώντας το καθορισμένο φορμά και πάροχο μορφής. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας τον καθορισμένο πάροχο μορφής και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας τα καθορισμένα φορμά και πάροχο μορφής, και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας το καθορισμένο φορμά, πάροχο μορφής και στυλ, και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας τα καθορισμένα φορμά, πάροχο μορφής και στυλ, και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Μετατρέπει τη συμβολοσειρά σε ισοδύναμο αντικείμενο [TimeSpan](./) χρησιμοποιώντας το καθορισμένο φορμά και πάροχο μορφής, και επιστρέφει το αποτέλεσμα της μετατροπής. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει ένα αντικείμενο [TypeInfo](../typeinfo/) που αντιπροσωπεύει τη δομή [TimeSpan](./). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [MaxValue](./maxvalue/) | Το αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το μεγαλύτερο δυνατό διάστημα. |
| static [MinValue](./minvalue/) | /// Το αντικείμενο [TimeSpan](./) που αντιπροσωπεύει το μικρότερο δυνατό διάστημα. |
| static constexpr [TicksPerDay](./ticksperday/) | Ο αριθμός των διαστημάτων των 100 νανοδευτερολέπτων σε μια ημέρα (διάστημα 24 ωρών). |
| static constexpr [TicksPerHour](./ticksperhour/) | Ο αριθμός των διαστημάτων των 100 νανοδευτερολέπτων σε μια ώρα. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Ο αριθμός των διαστημάτων των 100 νανοδευτερολέπτων σε ένα χιλιόδευτο. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Ο αριθμός των διαστημάτων των 100 νανοδευτερολέπτων σε ένα λεπτό. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Ο αριθμός των διαστημάτων των 100 νανοδευτερολέπτων σε ένα δευτερόλεπτο. |
| static [Zero](./zero/) | Το αντικείμενο [TimeSpan](./) που αντιπροσωπεύει μηδενικό διάστημα. |
## Παρατηρήσεις



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
Αριθμός ticks: 260928000000000
Αριθμός χιλιοστών: 0
Συνολικός αριθμός χιλιοστών: 2.60928e+10
Αριθμός λεπτών: 0
Συνολικός αριθμός λεπτών: 434880
Αριθμός ωρών: 0
Συνολικός αριθμός ωρών: 0
Αριθμός ημερών: 302
Συνολικός αριθμός ημερών: 302
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)