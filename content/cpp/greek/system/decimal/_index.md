---
title: Decimal
second_title: Aspose.Slides για C++ Αναφορά API
description: "Αντιπροσωπεύει έναν δεκαδικό αριθμό. Αυτός ο τύπος πρέπει να κατανεμηθεί στην στοίβα και να περάσει στις συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 261
url: /el/system/decimal/
---
## Decimal κλάση

Αντιπροσωπεύει έναν δεκαδικό αριθμό. Αυτός ο τύπος πρέπει να κατανεμηθεί στην στοίβα και να περάσει στις συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class Decimal
```

## Μέθοδοι

| Method | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Προσθέτει δύο καθορισμένες τιμές [Decimal](./). |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Επιστρέφει τη μικρότερη ακέραια τιμή που είναι μεγαλύτερη ή ίση με τη συγκεκριμένη τιμή. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Καθορίζει εάν η τιμή που αναπαριστά το πρώτο αντικείμενο [Decimal](./) είναι μικρότερη, ίση ή μεγαλύτερη από την τιμή που αναπαριστά το δεύτερο αντικείμενο [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Καθορίζει εάν η τιμή που αναπαριστά το τρέχον αντικείμενο είναι μικρότερη, ίση ή μεγαλύτερη από την τιμή που αναπαριστά το καθορισμένο αντικείμενο. |
|  [Decimal](./decimal/)() | Δημιουργεί μία παρουσία που αντιπροσωπεύει το 0. |
|  [Decimal](./decimal/)(std::int8_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::int16_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::int32_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::int64_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::uint8_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::uint16_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::uint32_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(std::uint64_t) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(**float**) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
|  [Decimal](./decimal/)(**double**) | Δημιουργεί μία παρουσία που αντιπροσωπεύει την καθορισμένη τιμή. |
| explicit  [Decimal](./decimal/)(const std::string\&) | Δημιουργεί μία παρουσία που αντιπροσωπεύει μια τιμή της οποίας η συμβολοσειρά αναπαράστασης καθορίζεται ως μια παρουσία της κλάσης std::string. |
|  [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Δημιουργεί ένα αντικείμενο [Decimal](./) από τα καθορισμένα συστατικά. |
|  [Decimal](./decimal/)(const [Decimal](./)\&) | Δημιουργεί μια παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει τον ίδιο αριθμό με το καθορισμένο αντικείμενο [Decimal](./). |
|  [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Δημιουργεί μια παρουσία της κλάσης [Decimal](./) από έναν ακέραιο πίνακα που περιέχει δυαδική αναπαράσταση. |
|  [Decimal](./decimal/)(std::nullptr_t) | Πάντα εγείρει το ArgumentNullException. |
|  [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Δημιουργεί μια παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει την καθορισμένη τιμή. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Διαιρεί δύο καθορισμένες τιμές [Decimal](./). |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Καθορίζει εάν οι τιμές που αναπαριστώνται από το τρέχον αντικείμενο και το καθορισμένο αντικείμενο είναι ίσες. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Καθορίζει εάν οι τιμές που αναπαριστώνται από το τρέχον αντικείμενο και το καθορισμένο αντικείμενο είναι ίσες. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Καθορίζει εάν οι τιμές που αναπαριστώνται από τα καθορισμένα αντικείμενα είναι ίσες. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Επιστρέφει τη μεγαλύτερη ακέραια τιμή που είναι μικρότερη ή ίση με τη συγκεκριμένη τιμή. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) τη συγκεκριμένη τιμή νομίσματος OLE στην ισοδύναμη τιμή [Decimal](./). NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Μετατρέπει το καθορισμένο αντικείμενο [Decimal](./) σε δυαδική αναπαράσταση της τιμής που αντιπροσωπεύει. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) την καθορισμένη τιμή [Decimal](./) σε έναν πίνακα bytes. |
| int [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Αποκτά τον κωδικό τύπου αντικειμένου. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Πολλαπλασιάζει δύο καθορισμένες τιμές [Decimal](./). |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που προκύπτει από την αντιστροφή της τιμής που αναπαριστά το καθορισμένο αντικείμενο. |
| explicit  [operator bool](./operator_bool/)() const | Μετατρέπει την τιμή που αναπαριστά το τρέχον αντικείμενο σε λογική τιμή. |
| explicit  [operator double](./operator_double/)() const | Μετατρέπει την τιμή που αναπαριστά το τρέχον αντικείμενο σε αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| explicit  [operator float](./operator_float/)() const | Μετατρέπει την τιμή που αναπαριστά το τρέχον αντικείμενο σε αριθμό κινητής υποδιαστολής απλής ακρίβειας. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Καθορίζει εάν οι τιμές που αναπαριστώνται από το τρέχον αντικείμενο και το καθορισμένο αντικείμενο δεν είναι ίσες. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Καθορίζει εάν η τιμή που αναπαριστά το τρέχον αντικείμενο διαφέρει από το 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που είναι αποτέλεσμα της λειτουργίας modulo με τις τιμές που αντιπροσωπεύουν τα τρέχοντα και τα καθορισμένα αντικείμενα. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Αναθέτει στο τρέχον αντικείμενο μια νέα τιμή που είναι αποτέλεσμα της λειτουργίας modulo με τις τιμές που αντιπροσωπεύουν τα τρέχοντα και τα καθορισμένα αντικείμενα. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που είναι αποτέλεσμα του πολλαπλασιασμού των τιμών που αντιπροσωπεύουν το τρέχον και το καθορισμένο αντικείμενο. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Αναθέτει στο τρέχον αντικείμενο μια νέα τιμή που είναι αποτέλεσμα του πολλαπλασιασμού των τιμών που αντιπροσωπεύουν το τρέχον και το καθορισμένο αντικείμενο. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που είναι άθροισμα των τιμών που αντιπροσωπεύουν το τρέχον και το καθορισμένο αντικείμενο. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Αυξάνει την τιμή που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Αναθέτει στο τρέχον αντικείμενο μια νέα τιμή που είναι άθροισμα των τιμών που αντιπροσωπεύουν το τρέχον και το καθορισμένο αντικείμενο. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που είναι το αποτέλεσμα της αφαίρεσης της τιμής που αντιπροσωπεύει το καθορισμένο αντικείμενο από την τιμή που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Decimal](./) [operator-](./operator_minus/)() const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που προκύπτει από την αντιστροφή της τιμής που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Μειώνει την τιμή που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Αναθέτει στο τρέχον αντικείμενο μια νέα τιμή που είναι το αποτέλεσμα της αφαίρεσης της τιμής που αντιπροσωπεύει το καθορισμένο αντικείμενο από την τιμή που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Επιστρέφει μια νέα παρουσία της κλάσης [Decimal](./) που αντιπροσωπεύει μια τιμή που είναι αποτέλεσμα της διαίρεσης της τιμής που αντιπροσωπεύει το τρέχον αντικείμενο με την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Αναθέτει στο τρέχον αντικείμενο μια νέα τιμή που είναι αποτέλεσμα της διαίρεσης της τιμής που αντιπροσωπεύει το τρέχον αντικείμενο με την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Καθορίζει εάν η τιμή που αντιπροσωπεύει το τρέχον αντικείμενο είναι μικρότερη από την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Καθορίζει εάν η τιμή που αντιπροσωπεύει το τρέχον αντικείμενο είναι μικρότερη ή ίση με την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Αναθέτει την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο στο τρέχον αντικείμενο. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Καθορίζει εάν οι τιμές που αντιπροσωπεύουν το τρέχον και το καθορισμένο αντικείμενο είναι ίσες. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Καθορίζει εάν η τιμή που αντιπροσωπεύει το τρέχον αντικείμενο είναι 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Καθορίζει εάν η τιμή που αντιπροσωπεύει το τρέχον αντικείμενο είναι μεγαλύτερη από την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Καθορίζει εάν η τιμή που αντιπροσωπεύει το τρέχον αντικείμενο είναι μεγαλύτερη ή ίση με την τιμή που αντιπροσωπεύει το καθορισμένο αντικείμενο. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συμβολοσειρά που αναπαριστά έναν δεκαδικό αριθμό σε ισοδύναμη παρουσία της κλάσης [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Μετατρέπει τη συμβολοσειρά που αναπαριστά έναν δεκαδικό αριθμό σε ισοδύναμη παρουσία της κλάσης [Decimal](./) χρησιμοποιώντας το καθορισμένο στυλ. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συμβολοσειρά που αναπαριστά έναν δεκαδικό αριθμό σε ισοδύναμη παρουσία της κλάσης [Decimal](./) χρησιμοποιώντας τον καθορισμένο πάροχο μορφής. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συμβολοσειρά που αναπαριστά έναν δεκαδικό αριθμό σε ισοδύναμη παρουσία της κλάσης [Decimal](./) χρησιμοποιώντας το καθορισμένο στυλ και πάροχο μορφής. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Υπολογίζει το υπόλοιπο μετά το διαίρεση δύο τιμών [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Στρογγυλοποιεί τη συγκεκριμένη τιμή στον πλησιέστερο ακέραιο αριθμό. Ένα παράμετρος ορίζει τη συμπεριφορά της συνάρτησης εάν η συγκεκριμένη τιμή είναι εξίσου κοντά σε δύο πλησιέστατους αριθμούς. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Στρογγυλοποιεί τη συγκεκριμένη τιμή στην πλησιέστερη τιμή με τον καθορισμένο αριθμό δεκαδικών ψηφίων. Ένα παράμετρος ορίζει τη συμπεριφορά της συνάρτησης εάν η συγκεκριμένη τιμή είναι εξίσου κοντά σε δύο πλησιέστατους αριθμούς. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Αφαιρεί μια καθορισμένη τιμή [Decimal](./) από μια άλλη. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 8-bit χωρίς πρόσημο. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε αριθμό κινητής υποδιαστολής διπλής ακρίβειας. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 16-bit με πρόσημο. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 32-bit με πρόσημο. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 64-bit με πρόσημο. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) τη συγκεκριμένη τιμή [Decimal](./) σε ισοδύναμη τιμή νομίσματος OLE. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 8-bit με πρόσημο. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε αριθμό κινητής υποδιαστολής απλής ακρίβειας. |
| std::string [ToStdString](./tostdstring/)() const | Επιστρέφει μια παρουσία του std::string που περιέχει τη συμβολοσειρά αναπαράστασης της τιμής που αντιπροσωπεύει το αντικείμενο. |
| [String](../string/) [ToString](./tostring/)() const | Επιστρέφει τη συμβολοσειρά αναπαράστασης της τιμής που αντιπροσωπεύει το αντικείμενο. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Μετατρέπει το τρέχον αντικείμενο σε συμβολοσειρά χρησιμοποιώντας τις πληροφορίες μορφοποίησης ειδικές για την πολιτισμική ρύθμιση. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Μετατρέπει το τρέχον αντικείμενο στη συμβολοσειρά του χρησιμοποιώντας τη συγκεκριμένη μορφή συμβολοσειράς και τις πληροφορίες μορφοποίησης ειδικές για την πολιτισμική ρύθμιση που παρέχονται από το καθορισμένο αντικείμενο [IFormatProvider](../iformatprovider/). |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Επιστρέφει τη συμβολοσειρά αναπαράστασης της τιμής που αντιπροσωπεύει το αντικείμενο. Για εσωτερική χρήση. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 16-bit χωρίς πρόσημο. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 32-bit χωρίς πρόσημο. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Μετατρέπει την τιμή [Decimal](./) σε ακέραιο 64-bit χωρίς πρόσημο. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Επιστρέφει το αντικείμενο [Decimal](./) που αντιπροσωπεύει μια τιμή της οποίας το ακέραιο μέρος είναι ίσο με το ακέραιο μέρος της τιμής που αντιπροσωπεύει το καθορισμένο αντικείμενο [Decimal](./), με όλα τα δεκαδικά ψηφία απορριφθέντα. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει τη συμβολοσειρά αναπαράστασης ενός αριθμού στην ισοδύναμη τιμή [Decimal](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει τη συμβολοσειρά αναπαράστασης ενός αριθμού στην ισοδύναμη τιμή [Decimal](./) χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Επιστρέφει μια αναφορά στο αντικείμενο [TypeInfo](../typeinfo/) που αντιπροσωπεύει τις πληροφορίες τύπου της κλάσης [Decimal](./). |
|  [~Decimal](./~decimal/)() | Καταστροφέας. |

## Πεδία

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Αντιπροσωπεύει τον μεγαλύτερο αριθμό που μπορεί να αναπαρασταθεί από την κλάση [Decimal](./). |
| static [MinusOne](./minusone/) | Αντιπροσωπεύει τον αριθμό -1. |
| static [MinValue](./minvalue/) | Αντιπροσωπεύει τον μικρότερο αριθμό που μπορεί να αναπαρασταθεί από την κλάση [Decimal](./). |
| static [One](./one/) | Αντιπροσωπεύει τον αριθμό 1. |
| static [Zero](./zero/) | Αντιπροσωπεύει τον αριθμό 0. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | Ένα ψευδώνυμο για το Detail::decimal_number_type. |

## Σχόλια

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)