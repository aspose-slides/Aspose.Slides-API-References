---
title: Char
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει μεθόδους για τη διαχείριση χαρακτήρων που αναπαρίστανται ως μονάδες κώδικα UTF-16. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιότυπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.
type: docs
weight: 170
url: /el/system/char/
---
## Char κλάση

Παρέχει μεθόδους για τη διαχείριση χαρακτήρων που αναπαρίστανται ως μονάδες κώδικα UTF-16. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανόνες.

```cpp
class Char
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static [String](../string/) [ConvertFromUtf32](./convertfromutf32/)(**uint32_t**) | Μετατρέπει μονάδα κώδικα UTF-32 σε μια παρουσία της κλάσης [System::String](../string/). |
| static int [ConvertToUtf32](./converttoutf32/)(char_t, char_t) | Μετατρέπει το καθορισμένο ζεύγος αναπλαστικών UTF-16 σε μονάδα κώδικα UTF-32. |
| static int [ConvertToUtf32](./converttoutf32/)(const [String](../string/)\&, int) | Μετατρέπει την τιμή ενός χαρακτήρα κωδικοποιημένου σε UTF-16 ή ζεύγους αναπλαστικών σε μια καθορισμένη θέση στήν συμβολοσειρά σε μονάδα κώδικα UTF-32. |
| static **double** [GetNumericValue](./getnumericvalue/)(char_t) | Μετατρέπει τον καθορισμένο χαρακτήρα UTF-16 σε αριθμητική τιμή κινητής υποδιαστολής διπλής ακρίβειας. |
| static [Globalization::UnicodeCategory](../../system.globalization/unicodecategory/) [GetUnicodeCategory](./getunicodecategory/)(char_t) | Επιστρέφει μια τιμή που αντιπροσωπεύει την κατηγορία Unicode του καθορισμένου χαρακτήρα. |
| static constexpr **bool** [IsAsciiWhiteSpace](./isasciiwhitespace/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως χαρακτήρας λευκού διαστήματος ASCII. |
| static **bool** [IsControl](./iscontrol/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως χαρακτήρας ελέγχου Unicode. |
| static **bool** [IsControl](./iscontrol/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως χαρακτήρας ελέγχου Unicode. |
| static **bool** [IsDigit](./isdigit/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως δεκαδικό ψηφίο. |
| static **bool** [IsDigit](./isdigit/)(const [String](../string/)\&, const **int32_t**) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς ταξινομείται ως δεκαδικό ψηφίο. |
| static **bool** [IsDigit](./isdigit/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως δεκαδικό ψηφίο. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const [String](../string/)\&, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς είναι μονάδα κώδικα υψηλού αναπλαστικού UTF-16. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων είναι υψηλό αναπλαστικό. |
| static **bool** [IsHighSurrogate](./ishighsurrogate/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας είναι υψηλό αναπλαστικό. |
| static **bool** [IsLetter](./isletter/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως γράμμα Unicode. |
| static **bool** [IsLetter](./isletter/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως γράμμα Unicode. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως γράμμα Unicode ή δεκαδικό ψηφίο. |
| static **bool** [IsLetterOrDigit](./isletterordigit/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως γράμμα Unicode ή δεκαδικό ψηφίο. |
| static **bool** [IsLower](./islower/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως πεζό γράμμα. |
| static **bool** [IsLower](./islower/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως πεζό γράμμα. |
| static **bool** [IsLower](./islower/)(const [String](../string/)\&, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς ταξινομείται ως πεζό γράμμα. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων είναι χαμηλό αναπλαστικό. |
| static **bool** [IsLowSurrogate](./islowsurrogate/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας είναι χαμηλό αναπλαστικό. |
| static **bool** [IsNumber](./isnumber/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως αριθμός. |
| static **bool** [IsNumber](./isnumber/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως αριθμός. |
| static **bool** [IsPunctuation](./ispunctuation/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως χαρακτήρας στίξης. |
| static **bool** [IsPunctuation](./ispunctuation/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως χαρακτήρας στίξης. |
| static **bool** [IsSeparator](./isseparator/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως χαρακτήρας διαχωριστικού. |
| static **bool** [IsSeparator](./isseparator/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως χαρακτήρας διαχωριστικού. |
| static **bool** [IsSurrogate](./issurrogate/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας είναι μονάδα κώδικα αναπλαστικού UTF-16. |
| static **bool** [IsSurrogate](./issurrogate/)(const [String](../string/)\&, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς είναι μονάδα κώδικα αναπλαστικού UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(char_t, char_t) | Καθορίζει αν οι δύο καθορισμένοι χαρακτήρες αποτελούν ζεύγος αναπλαστικών UTF-16. |
| static **bool** [IsSurrogatePair](./issurrogatepair/)(const [String](../string/)\&, int) | Καθορίζει αν δύο διαδοχικοί χαρακτήρες στο καθορισμένο buffer χαρακτήρων αποτελούν ζεύγος αναπλαστικών. |
| static **bool** [IsSymbol](./issymbol/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως συμβολικός χαρακτήρας. |
| static **bool** [IsSymbol](./issymbol/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως συμβολικός χαρακτήρας. |
| static **bool** [IsUpper](./isupper/)(const [String](../string/)\&, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς ταξινομείται ως κεφαλαίο γράμμα. |
| static **bool** [IsUpper](./isupper/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως κεφαλαίο γράμμα. |
| static **bool** [IsUpper](./isupper/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως κεφαλαίο γράμμα. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const char_t *, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση του καθορισμένου buffer χαρακτήρων ταξινομείται ως χαρακτήρας λευκού διαστήματος. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(char_t) | Καθορίζει αν ο καθορισμένος χαρακτήρας ταξινομείται ως χαρακτήρας λευκού διαστήματος. |
| static **bool** [IsWhiteSpace](./iswhitespace/)(const [String](../string/)\&, int) | Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση της καθορισμένης συμβολοσειράς ταξινομείται ως χαρακτήρας λευκού διαστήματος. |
| static char_t [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τον πρώτο και μοναδικό χαρακτήρα της καθορισμένης συμβολοσειράς σε τιμή τύπου char_t. |
| static char_t [ToLower](./tolower/)(char_t) | Μετατρέπει τον καθορισμένο χαρακτήρα σε πεζά. |
| static char_t [ToLower](./tolower/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Μετατρέπει τον καθορισμένο χαρακτήρα σε πεζά. |
| static char_t [ToLowerInvariant](./tolowerinvariant/)(char_t) | Μετατρέπει τον καθορισμένο χαρακτήρα σε πεζά. |
| static char_t [ToUpper](./toupper/)(char_t) | Μετατρέπει τον καθορισμένο χαρακτήρα σε κεφαλαία. |
| static char_t [ToUpper](./toupper/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Μετατρέπει τον καθορισμένο χαρακτήρα σε κεφαλαία. |
| static char_t [ToUpperInvariant](./toupperinvariant/)(char_t) | Μετατρέπει τον καθορισμένο χαρακτήρα σε κεφαλαία. |
| static **bool** [TryParse](./tryparse/)(const [System::String](../string/)\&, char_t\&) | Προσπαθεί να μετατρέψει μια συμβολοσειρά που αποτελείται από έναν μοναδικό χαρακτήρα σε χαρακτήρα UTF-16. Η λειτουργία επιτυγχάνει μόνο όταν η εισαγόμενη συμβολοσειρά δεν είναι κενή (null) και έχει μήκος ακριβώς ενός χαρακτήρα. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)