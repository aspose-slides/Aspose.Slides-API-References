---
title: String
second_title: Aspose.Slides για την αναφορά API C++
description: "Κλάση String που χρησιμοποιείται σε όλη τη βιβλιοθήκη. Αντικαθιστά το C# System.String κατά τη μετάφραση κώδικα. Για λόγους βελτιστοποίησης, δεν θεωρείται υποκατηγορία του Object. Αυτός ο τύπος θα πρέπει να κατανεμηθεί στην στοίβα και να περνάει στις συναρτήσεις ως τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση System::SmartPtr για τη διαχείριση αντικειμένων αυτού του τύπου."
type: docs
weight: 1249
url: /el/system/string/
---
## Κλάση String

[String](./) κλάση που χρησιμοποιείται σε όλη τη βιβλιοθήκη. Αντικαθιστά το C# [System.String](./) κατά τη μετάφραση κώδικα. Για λόγους βελτιστοποίησης, δεν θεωρείται υποκατηγορία του [Object](../object/). Αυτός ο τύπος πρέπει να κατανεμηθεί στην στοίβα και να περνάται σε συναρτήσεις με τιμή ή με αναφορά. Ποτέ μην χρησιμοποιείτε την κλάση [System::SmartPtr](../smartptr/) για τη διαχείριση αντικειμένων αυτού του τύπου.

```cpp
class String
```

## Μέθοδοι

| Method | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) είναι τύπος τιμής στην πλευρά C++ που υλοποιεί σιωπηρά (χωρίς κληρονομικότητα) ορισμένες διεπαφές. |
| const UChar * [begin](./begin/)() const | Επιστρέφει δείκτη στην αρχή του πραγματικού buffer της συμβολοσειράς. Ποτέ δεν επανεκχωρεί τίποτα. Δεν εγγυάται ότι το buffer είναι null-terminated. |
| [String](./) [Clone](./clone/)() const | Δημιουργεί ένα αντίγραφο της τρέχουσας συμβολοσειράς. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Συγκρίνει δύο υποσυμβολοσυμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Συγκρίνει δύο υποσυμβολοσυμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Συγκρίνει δύο συμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Συγκρίνει δύο συμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Συγκρίνει δύο συμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Συγκρίνει δύο συμβολοσειρές με βάση μικρότερο-ίσον-μεγαλύτερο. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Συγκρίνει δύο συμβολοσειρές σε λειτουργία ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Συγκρίνει δύο συμβολοσειρές σε λειτουργία ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Συγκρίνει δύο συμβολοσειρές σε στυλ 'μικρότερο-ίσον-μεγαλύτερο'. Χρησιμοποιεί την τρέχουσα τοπική ρύθμιση. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Συνενώνει συμβολοσειρές. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Συνενώνει συμβολοσειρές. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Συνενώνει συμβολοσειρές. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Συνενώνει συμβολοσειρές. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Ελέγχει αν το str είναι υποσυμβολοσειρά της τρέχουσας συμβολοσειράς. |
| **bool** [Contains](./contains/)(char16_t) const | Ελέγχει αν η συμβολοσειρά περιέχει τον δεδομένο χαρακτήρα. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Δημιουργεί αντίγραφο της συμβολοσειράς. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Αντιγράφει χαρακτήρες της συμβολοσειράς σε υπάρχοντα στοιχεία του πίνακα. Δεν γίνεται αλλαγή μεγέθους. |
| const UChar * [end](./end/)() const | Επιστρέφει δείκτη στο τέλος του πραγματικού buffer της συμβολοσειράς. Ποτέ δεν επανεκχωρεί τίποτα. Δεν εγγυάται ότι το buffer είναι null-terminated. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Ελέγχει αν η συμβολοσειρά τελειώνει με την καθορισμένη υποσυμβολοσειρά. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) σύγκριση ισότητας. Υποστηρίζονται διάφορες λειτουργίες που παρέχονται από την απαρίθμηση StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) σύγκριση ισότητας. Χρησιμοποιεί τη λειτουργία σύγκρισης [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Ισοδυναμική σύγκριση δύο συμβολοσειρών χρησιμοποιώντας τη λειτουργία σύγκρισης Ordial. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Ισοδυναμική σύγκριση δύο συμβολοσειρών. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Προσπαθεί να μετατρέψει ένα [String](./) σε συμβολοσειρά ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Διαμορφώνει τη συμβολοσειρά σε στυλ C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Διαμορφώνει τη συμβολοσειρά σε στυλ C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Διαμορφώνει τη συμβολοσειρά σε στυλ C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Διαμορφώνει τη συμβολοσειρά σε στυλ C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Διαμορφώνει τη συμβολοσειρά σε στυλ C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Δημιουργεί [String](./) από συμβολοσειρά ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Δημιουργεί [String](./) από συμβολοσειρά ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Δημιουργεί [String](./) από συμβολοσειρά ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Δημιουργεί [String](./) από συμβολοσειρά utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Δημιουργεί [String](./) από συμβολοσειρά utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Δημιουργεί [String](./) από συμβολοσειρά utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Δημιουργεί [String](./) από συμβολοσειρά utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Δημιουργεί [String](./) από συμβολοσειρά utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Δημιουργεί [String](./) από συμβολοσειρά utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Δημιουργεί [String](./) από widestring. |
| int [get_Length](./get_length/)() const | Λαμβάνει το μήκος της συμβολοσειράς. |
| int [GetHashCode](./gethashcode/)() const | Δημιουργεί hash της συμβολοσειράς. Υλοποιείται στο ICU, δεν ταιριάζει με τα hash στο C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Αναζήτηση προώθησης υποσυμβολοσυμβολοσειράς. |
| int [IndexOf](./indexof/)(char_t, int) const | Αναζήτηση προώθησης χαρακτήρα. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Αναζήτηση προώθησης χαρακτήρα σε υποσυμβολοσυμβολοσειρά. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Αναζήτηση προώθησης υποσυμβολοσυμβολοσειράς. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Αναζήτηση προώθησης υποσυμβολοσυμβολοσειράς. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Αναζήτηση προώθησης υποσυμβολοσυμβολοσειράς. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Αναζήτηση προώθησης υποσυμβολοσυμβολοσειράς. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Αναζήτηση προώθησης χαρακτήρα. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Αναζητά διαδοχικά όλους τους χαρακτήρες του str σε αυτήν. Εάν βρεθεί ο πρώτος χαρακτήρας, επιστρέφεται η θέση του· διαφορετικά ψάχνει τον δεύτερο κ.λπ. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε ολόκληρη τη συμβολοσειρά. Συγκρίνει τον πρώτο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρες του anyOf, μετά τον δεύτερο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που ταιριάζει με κάποιον από τους στόχους. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε υποσυμβολοσυμβολοσειρά. Συγκρίνει τον πρώτο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρες του anyOf, μετά τον δεύτερο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που ταιριάζει με κάποιον από τους στόχους. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε υποσυμβολοσυμβολοσειρά. Συγκρίνει τον πρώτο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρα του anyOf, μετά τον δεύτερο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που ταιριάζει με κάποιον από τους στόχους. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Εισάγει υποσυμβολοσυμβολοσειρά στη συγκεκριμένη θέση. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ελέγχει αν το αντικείμενο συμβολοσειράς είναι του τύπου που καθορίζεται από το [TypeInfo](../typeinfo/) που περάστηκε. |
| **bool** [IsAsciiString](./isasciistring/)() const | Δείχνει αν ένα [String](./) περιέχει μόνο σύμβολα ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Ελέγχει αν η συμβολοσειρά είναι και μη-null και κενή. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Ελέγχει αν η Unicode συμβολοσειρά είναι κανονικοποιημένη με τη μορφή κανονικοποίησης που δίνεται. |
| **bool** [IsNull](./isnull/)() const | Ελέγχει αν η συμβολοσειρά θεωρείται null. [String](./) είναι null μόνο αν δημιουργείται μέσω του κατασκευαστή [String()](./string/), μετακινείται, αντιγράφεται ή εκχωρείται από null συμβολοσειρά ή κλήθηκε η μέθοδος [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Ελέγχει αν η συμβολοσειρά είναι κενή ή θεωρείται null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Ελέγχει αν η δοσμένη συμβολοσειρά είναι null ή κενή. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Δείχνει αν μια συγκεκριμένη συμβολοσειρά είναι null, κενή ή αποτελείται μόνο από λευκούς χαρακτήρες. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Ενώνει πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Ενώνει πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Ενώνει πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Ενώνει πίνακα χρησιμοποιώντας τη συμβολοσειρά ως διαχωριστικό. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Αναζήτηση οπισθοδρόμησης υποσυμβολοσυμβολοσειράς. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Αναζήτηση οπισθοδρόμησης υποσυμβολοσυμβολοσειράς. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Αναζήτηση οπισθοδρόμησης υποσυμβολοσυμβολοσειράς. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Αναζήτηση οπισθοδρόμησης υποσυμβολοσυμβολοσειράς. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Αναζήτηση οπισθοδρόμησης χαρακτήρα. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Αναζήτηση οπισθοδρόμησης χαρακτήρα. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Αναζήτηση οπισθοδρόμησης χαρακτήρα. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε ολόκληρη τη συμβολοσειρά προς τα πίσω. Συγκρίνει τον τελευταίο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρες του anyOf, μετά τον προηγούμενο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που βρέθηκε. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε υποσυμβολοσυμβολοσειρά προς τα πίσω. Συγκρίνει τον τελευταίο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρες του anyOf, μετά τον προηγούμενο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που βρέθηκε. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Αναζητά οποιονδήποτε από τους δοσμένους χαρακτήρες σε υποσυμβολοσυμβολοσειρά προς τα πίσω. Συγκρίνει τον τελευταίο χαρακτήρα της συμβολοσειράς με όλους τους χαρακτήρες του anyOf, μετά τον προηγούμενο κ.λπ. Επιστρέφει το ευρετήριο του πρώτου που βρέθηκε. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Κανονικοποιεί τη Unicode συμβολοσειρά με τη μορφή κανονικοποίησης που δίνεται. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Μετατρέπει τη συμβολοσειρά σε read-only span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Χειριστής ανισότητας. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Ελέγχει αν η συμβολοσειρά δεν είναι null. Εφαρμόζει την ίδια λογική με την κλήση [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) τελεστής συνένωσης. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) συνένωση με κυριολεκτικό συμβολοσειράς ή δείκτη σε χαρακτήρα. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Προσθέτει χαρακτήρα στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(int) const | Προσθέτει την αναπαράσταση της ακεραίας τιμής στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Προσθέτει την αναπαράσταση της μη-υπογεγραμμένης ακεραίας τιμής στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Προσθέτει την αναπαράσταση της αριθμητικής τιμής κινητής υποδιαστολής στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Προσθέτει την αναπαράσταση της ακεραίας τιμής int64 στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Προσθέτει την αναπαράσταση του αντικειμένου αναφοράς τύπου T στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Προσθέτει την αναπαράσταση του αντικειμένου αναφοράς τύπου T στο τέλος της συμβολοσειράς. |
| [String](./) [operator+](./operator_plus/)(T) const | Προσθέτει την αναπαράσταση της λογικής τιμής στο τέλος της συμβολοσειράς. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Τελεστής ανάθεσης συνένωσης. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Τελεστής ανάθεσης συνένωσης. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Συγκρίνει τις συμβολοσειρές κατά σειρά. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Τελεστής ανάθεσης. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Τελεστής ανάθεσης κίνησης. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Τελεστής σύγκρισης ισότητας. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ελέγχει αν η συμβολοσειρά είναι null. Εφαρμόζει την ίδια λογική με την κλήση [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Συγκρίνει τις συμβολοσειρές κατά σειρά. |
| char_t [operator[]](./operator[]/)(int) const | Λαμβάνει τον χαρακτήρα στη συγκεκριμένη θέση. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Προσθέτει γεμιστικό στα αριστερά της αρχικής συμβολοσειράς. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Προσθέτει γεμιστικό στα δεξιά της αρχικής συμβολοσειράς. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Επιστρέφει αντίστροφο iterator στο τελευταίο χαρακτήρα (εφόσον υπάρχει) του πραγματικού buffer της συμβολοσειράς. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Εξάγει όλο το περιεχόμενο εκτός της υποσυμβολοσυμβολοσειράς από την τρέχουσα συμβολοσειρά. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Επιστρέφει αντίστροφο iterator πριν τον πρώτο χαρακτήρα (εφόσον υπάρχει) του πραγματικού buffer της συμβολοσειράς. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Αντικαθιστά όλες τις εμφανίσεις του χαρακτήρα στη συμβολοσειρά. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Αντικαθιστά όλες τις εμφανίσεις της αναζήτησης σε αυτή τη συμβολοσειρά. |
| [String](./)\& [reset](./reset/)() | Ορίζει τη συμβολοσειρά σε null. Είναι ισοδύναμο με το 'string_variable_name = null' σε C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Ορίζει τον χαρακτήρα στη συγκεκριμένη θέση. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά χαρακτήρα. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά χαρακτήρα. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά έναν από τους δύο χαρακτήρες. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά έναν από τους καθορισμένους χαρακτήρες. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά έναν από τους καθορισμένους χαρακτήρες. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά υποσυμβολοσυμβολοσειρά. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά υποσυμβολοσυμβολοσειρά. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά υποσυμβολοσυμβολοσειρά. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Διαχωρίζει τη συμβολοσειρά κατά υποσυμβολοσυμβολοσειρά. Επί του παρόντος, υποστηρίζει μόνο πίνακες διαχωριστών με μηδέν ή ένα στοιχεία. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Ελέγχει αν η συμβολοσειρά αρχίζει με την καθορισμένη υποσυμβολοσυμβολοσειρά. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Ελέγχει αν η συμβολοσειρά αρχίζει με την καθορισμένη υποσυμβολοσυμβολοσειρά. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Ελέγχει αν η συμβολοσειρά αρχίζει με την καθορισμένη υποσυμβολοσυμβολοσειρά. |
|  [String](./string/)() | Προεπιλεγμένος κατασκευαστής. Δημιουργεί αντικείμενο συμβολοσειράς που θεωρείται null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε κυριολεκτικό συμβολοσειρά. Θεωρεί το κυριολεκτικό ως null-terminated string, υπολογίζει το μήκος βασιζόμενο στο μέγεθος του κυριολεκτικού. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε δείκτη σε συμβολοσειρά χαρακτήρων. Θεωρεί τη συμβολοσειρά ως null-terminated, υπολογίζει το μήκος βασιζόμενο στο null χαρακτήρα. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε κυριολεκτικό συμβολοσειρά. Θεωρεί το κυριολεκτικό ως null-terminated string σε UTF8, υπολογίζει το μήκος βασιζόμενο στο μέγεθος του κυριολεκτικού. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε δείκτη σε συμβολοσειρά χαρακτήρων. Θεωρεί τη συμβολοσειρά ως null-terminated σε UTF8, υπολογίζει το μήκος βασιζόμενο στο null χαρακτήρα. |
|  [String](./string/)(const char16_t *, int) | Δημιουργεί συμβολοσειρά από δείκτη σε συμβολοσειρά χαρακτήρων και ρητό μήκος. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Αρχικοποιεί μια νέα παρουσία της κλάσης [System.String](./) με τους Unicode χαρακτήρες που υποδεικνύονται από το καθορισμένο read-only span. |
|  [String](./string/)(const char *, int) | Δημιουργεί συμβολοσειρά από δείκτη σε συμβολοσειρά χαρακτήρων και ρητό μήκος. |
|  [String](./string/)(const char16_t *, int, int) | Δημιουργεί συμβολοσειρά από δείκτη σε συμβολοσειρά χαρακτήρων, ξεκινώντας από θέση με δεδομένο μήκος. |
| explicit  [String](./string/)(const char16_t, int) | Κατασκευαστής γεμίσματος. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Κατασκευαστής nullptr. Ορίζεται ως πρότυπο για την επίλυση προτεραιοτήτων με άλλους κατασκευαστές προτύπων. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε κυριολεκτικό widestring. Θεωρεί το κυριολεκτικό ως null-terminated string, υπολογίζει το μήκος βασιζόμενο στο μέγεθος του κυριολεκτικού. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται μετατροπές χωρίς ρητή κλήση. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Δημιουργεί συμβολοσειρά βασισμένη σε δείκτη σε widecharacter string. Θεωρεί τη συμβολοσειρά ως null-terminated, υπολογίζει το μήκος βασιζόμενο στο null χαρακτήρα. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται μετατροπές χωρίς ρητή κλήση. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Δημιουργεί συμβολοσειρά από δείκτη σε widecharacter string και ρητό μήκος. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται μετατροπές χωρίς ρητή κλήση. |
| explicit  [String](./string/)(const **wchar_t**, int) | Κατασκευαστής γεμίσματος. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται μετατροπές χωρίς ρητή κλήση. |
|  [String](./string/)(const [String](./)\&) | Κατασκευαστής αντιγραφής. |
|  [String](./string/)([String](./)\&&) | Κατασκευαστής μετακίνησης. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Μετατρέπει ολόκληρο τον πίνακα χαρακτήρων σε συμβολοσειρά. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Μετατρέπει υποδιάστημα πίνακα χαρακτήρων σε συμβολοσειρά. Εάν οι παράμετροι είναι εκτός ορίων πίνακα, δημιουργείται κενή συμβολοσειρά. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Ενσωματώνει την UnicodeString στην κλάση [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Κατασκευαστής μετακίνησης. |
| explicit  [String](./string/)(const std::wstring\&) | Δημιουργεί [String](./) από widestring. |
| explicit  [String](./string/)(const std::u16string\&) | Δημιουργεί [String](./) από συμβολοσειρά utf16. |
| explicit  [String](./string/)(const std::string\&) | Δημιουργεί [String](./) από συμβολοσειρά std::string σε μορφή UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Δημιουργεί [String](./) από συμβολοσειρά std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Εξάγει υποσυμβολοσυμβολοσειρά. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Εξάγει υποσυμβολοσυμβολοσειρά. |
| std::string [ToAsciiString](./toasciistring/)() const | Μετατρέπει τη συμβολοσειρά σε std::string. Χρησιμοποιεί κωδικοποίηση ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Μετατρέπει τη συμβολοσειρά ή υποσυμβολοσυμβολοσειρά σε πίνακα bytes. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Μετατρέπει τη συμβολοσειρά ή υποσυμβολοσυμβολοσειρά σε πίνακα χαρακτήρων. |
| [String](./) [ToLower](./tolower/)() const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε πεζά. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε πεζά χρησιμοποιώντας συγκεκριμένη πολιτισμική ρύθμιση. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε πεζά χρησιμοποιώντας αμετάβλητη πολιτισμική ρύθμιση. |
| [String](./) [ToString](./tostring/)() const | Περιτύλιγμα για τη διαχείριση της κλάσης [String](./) σε περιβάλλοντα όπου καλείται [ToString()](./tostring/) σε αντικείμενα τύπου τιμής. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Περιτύλιγμα για τη διαχείριση της κλάσης [String](./) σε περιβάλλοντα όπου καλείται [ToString()](./tostring/) σε αντικείμενα τύπου τιμής. |
| std::u16string [ToU16Str](./tou16str/)() const | Μετατρέπει τη συμβολοσειρά σε std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Μετατρέπει τη συμβολοσειρά σε std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε κεφαλαία. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε κεφαλαία χρησιμοποιώντας συγκεκριμένη πολιτισμική ρύθμιση. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Μετατρέπει όλους τους χαρακτήρες της συμβολοσειράς σε κεφαλαία χρησιμοποιώντας αμετάβλητη πολιτισμική ρύθμιση. |
| std::string [ToUtf8String](./toutf8string/)() const | Μετατρέπει τη συμβολοσειρά σε std::string. Χρησιμοποιεί κωδικοποίηση UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Μετατρέπει τη συμβολοσειρά σε std::wstring. |
| [String](./) [Trim](./trim/)() const | Αφαιρεί όλους τους λευκούς χαρακτήρες από την αρχή και το τέλος της συμβολοσειράς. |
| [String](./) [Trim](./trim/)(char_t) const | Αφαιρεί όλες τις εμφανίσεις του δοσμένου χαρακτήρα από την αρχή και το τέλος της συμβολοσειράς. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Αφαιρεί όλες τις εμφανίσεις των δοσμένων χαρακτήρων από την αρχή και το τέλος της συμβολοσειράς. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Αφαιρέει όλες τις εμφανίσεις των δοσμένων χαρακτήρων από την αρχή και το τέλος της συμβολοσειράς. |
| [String](./) [TrimEnd](./trimend/)() const | Αφαιρεί όλους τους λευκούς χαρακτήρες από το τέλος της συμβολοσειράς. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Αφαιρεί όλες τις εμφανίσεις του δοσμένου χαρακτήρα από το τέλος της συμβολοσειράς. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Αφαιρεί όλες τις εμφανίσεις των δοσμένων χαρακτήρων από το τέλος της συμβολοσειράς. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Αφαιρεί όλες τις εμφανίσεις των δοσμένων χαρακτήρων από το τέλος της συμβολοσειράς. |
| [String](./) [TrimStart](./trimstart/)() const | Αφαιρεί όλους τους λευκούς χαρακτήρες από την αρχή της συμβολοσειράς. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Αφαιρεί όλες τις εμφανίσεις του δοσμένου χαρακτήρα από την αρχή της συμβολοσειράς. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Αφαιρεί όλες τις εμφανίσεις των δοσμένων χαρακτήρων από την αρχή της συμβολοσειράς. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Αφαιρεί όλες τις εμφανίσεις των δοσμένων χαρακτήρων από την αρχή της συμβολοσειράς. |
| const UChar * [u_str](./u_str/)() const | Επιστρέφει buffer τύπου ICU με null-termination. Μπορεί να επανεκχωρήσει τη συμβολοσειρά. |
|  [~String](./~string/)() | Καταστροφέας. |

## Πεδία

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Κενή συμβολοσειρά. |
| static [Null](./null/) | Null συμβολοσειρά. |

## Alias τύπων

| Typedef | Description |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Τύπος αντίστροφου iterator. |

## Παρατηρήσεις



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Δημιουργεί μια συμβολοσειρά από τον πίνακα χαρακτήρων και την εμφανίζει.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Δημιουργεί μια συμβολοσειρά από τον πίνακα bytes και την εμφανίζει.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Κόβει (αφαιρεί κενά) την παρακάτω συμβολοσειρά και την εμφανίζει.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Εμφανίζει τον αριθμό των λέξεων στο .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)