---
title: Buffer
second_title: Αναφορά API του Aspose.Slides για C++
description: Περιέχει μεθόδους που χειρίζονται ακατέργαστους πίνακες byte. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιότυπων. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.
type: docs
weight: 144
url: /el/system/buffer/
---
## Buffer κλάση


Περιέχει μεθόδους που χειρίζονται ακατέργαστους πίνακες byte. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιότυπων. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με κανέναν τρόπο.

```cpp
class Buffer
```

## Μέθοδοι

| Method | Περιγραφή |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | Αντιγράφει έναν καθορισμένο αριθμό bytes από το buffer προέλευσης στο buffer προορισμού. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | Ερμηνεύει δύο καθορισμένους τυποποιημένους πίνακες ως ακατέργαστους πίνακες bytes και αντιγράφει δεδομένα από τον έναν στον άλλο. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | Καθορίζει τον αριθμό των bytes που καταλαμβάνονται από όλα τα στοιχεία του καθορισμένου πίνακα. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | Καθορίζει τον αριθμό των bytes που καταλαμβάνονται από όλα τα στοιχεία του καθορισμένου πίνακα. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | Καθορίζει τον αριθμό των bytes που καταλαμβάνονται από όλα τα στοιχεία του καθορισμένου πίνακα. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στην καθορισμένη μετατόπιση byte. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στην καθορισμένη μετατόπιση byte. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στην καθορισμένη μετατόπιση byte. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στην καθορισμένη μετατόπιση byte. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στην καθορισμένη μετατόπιση byte. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | Ερμηνεύει τον καθορισμένο τυποποιημένο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στην καθορισμένη μετατόπιση byte. |
## Παρατηρήσεις



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Δημιουργία και γέμισμα του πίνακα.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // Εκτύπωση των στοιχείων του πίνακα.
  Print(first, SIZE);

  // Δημιουργία πίνακα που περιέχει μέρος του πρώτου.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // Εκτύπωση των στοιχείων του δεύτερου πίνακα.
  Print(second, SIZE / 2);

  // Ορισμός της τιμής του στοιχείου στη θέση 0 και εκτύπωση των στοιχείων του πίνακα.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
Αυτό το παράδειγμα κώδικα παράγει την ακόλουθη έξοδο:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)