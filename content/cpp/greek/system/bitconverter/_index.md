---
title: BitConverter
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιέχει μεθόδους που εκτελούν μετατροπές της ακολουθίας byte σε τύπο τιμής και αντίστροφα. Πρόκειται για έναν στατικό τύπο χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με οποιονδήποτε τρόπο.
type: docs
weight: 66
url: /el/system/bitconverter/
---
## BitConverter κλάση

Περιέχει μεθόδους που εκτελούν μετατροπές σειράς byte σε τύπο τιμής και αντίστροφα. Αυτό είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπου. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με οποιονδήποτε τρόπο.

```cpp
class BitConverter
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Υποδεικνύει τη σειρά byte (endianness) της τρέχουσας αρχιτεκτονικής. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Επιστρέφει μια τιμή ακέραιου 64-bit της οποίας η δυαδική αναπαράσταση είναι ίση με τη δυαδική αναπαράσταση της καθορισμένης τιμής διπλής-ακρίβειας κινητής υποδιαστολής. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Μετατρέπει τη συγκεκριμένη τιμή boolean σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Μετατρέπει τη συγκεκριμένη τιμή char_t σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου 16-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου 32-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου 64-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου χωρίς πρόσημο 16-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου χωρίς πρόσημο 32-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Μετατρέπει τη συγκεκριμένη τιμή ακέραιου χωρίς πρόσημο 64-bit σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Μετατρέπει τη συγκεκριμένη τιμή μονής-ακρίβειας κινητής υποδιαστολής σε έναν πίνακα byte. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Μετατρέπει τη συγκεκριμένη τιμή διπλής-ακρίβειας κινητής υποδιαστολής σε έναν πίνακα byte. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Επιστρέφει μια τιμή διπλής-ακρίβειας κινητής υποδιαστολής η οποία είναι ισοδύναμη με την τιμή. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει ένα byte από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή boolean. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει ένα byte από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή boolean. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή char_t. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή char_t. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή διπλής-ακρίβειας κινητής υποδιαστολής. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή διπλής-ακρίβειας κινητής υποδιαστολής. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 16-bit. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 16-bit. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 32-bit. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 32-bit. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 64-bit. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου 64-bit. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή μονής-ακρίβειας κινητής υποδιαστολής. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή μονής-ακρίβειας κινητής υποδιαστολής. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Μετατρέπει όλες τις τιμές του καθορισμένου πίνακα byte στη δεκαεξαδική τους αναπαράσταση. Η περίπτωση των γραμμάτων στη δεκαεξαδική σημειογραφία και ο διαχωριστής μεταξύ γειτονικών bytes καθορίζονται μέσω αντίστοιχων ορισμάτων. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει τιμές του καθορισμένου πίνακα byte στη δεκαεξαδική τους αναπαράσταση αρχίζοντας από τον καθορισμένο δείκτη. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Μετατρέπει μια περιοχή τιμών του καθορισμένου πίνακα byte στη δεκαεξαδική τους αναπαράσταση. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 16-bit. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει δύο bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 16-bit. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 32-bit. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει τέσσερα bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 32-bit. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 64-bit. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Μετατρέπει οκτώ bytes από τον καθορισμένο πίνακα αρχίζοντας από το καθορισμένο δείκτη σε τιμή ακέραιου χωρίς πρόσημο 64-bit. |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Υποδεικνύει τη σειρά byte (endianness) της τρέχουσας αρχιτεκτονικής. true αν η αρχιτεκτονική είναι little endian, false διαφορετικά. |

## Σχόλια



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Δημιουργήστε τιμές για εκτύπωση.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Εκτυπώστε την τιμή και τα bytes της.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)