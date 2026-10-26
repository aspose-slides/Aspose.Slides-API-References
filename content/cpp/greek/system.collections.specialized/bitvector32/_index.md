---
title: BitVector32
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει ένα απλό ελαφρύ bit vector με εύκολη πρόσβαση ακέραιου ή Boolean σε αποθήκευση 32 bit.
type: docs
weight: 1
url: /el/system.collections.specialized/bitvector32/
---
## BitVector32 κλάση

Παρέχει ένα απλό ελαφρύ bit vector με εύκολη πρόσβαση ακέραιου ή [Boolean](../../system/boolean/) σε αποθήκευση 32 bit.

```cpp
class BitVector32
```

## Μέθοδοι

| Method | Description |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Αρχικοποιεί ένα νέο κενό στιγμιότυπο του [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [BitVector32](./) με τα καθορισμένα εσωτερικά δεδομένα. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής [BitVector32](./) με τις πληροφορίες στην καθορισμένη τιμή. |
| static **int32_t** [CreateMask](./createmask/)() | Δημιουργεί τη πρώτη μάσκα σε μια σειρά. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Δημιουργεί την επόμενη μάσκα σε μια σειρά. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Δημιουργεί την πρώτη ενότητα σε μια σειρά, με τη καθορισμένη μέγιστη τιμή. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Δημιουργεί την επόμενη ενότητα σε μια σειρά, με τη καθορισμένη μέγιστη τιμή. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Καθορίζει αν το καθορισμένο αντικείμενο είναι το ίδιο με το τρέχον. |
| **int32_t** [get_Data](./get_data/)() | επιστρέφει τα ακατέργαστα δεδομένα που αποθηκεύονται σε αυτό το bit vector... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Επιστρέφει έναν κωδικό κατατεμαχισμού για το τρέχον αντικείμενο. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Λαμβάνει μια τιμή που δείχνει αν όλα τα καθορισμένα bits είναι ορισμένα. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Λαμβάνει την τιμή για την καθορισμένη ενότητα. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Ορίζει μια τιμή που υποδεικνύει αν όλα τα καθορισμένα bits είναι ορισμένα. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Ορίζει την τιμή για την καθορισμένη ενότητα. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Μετρέπει τη τιμή που αντιπροσωπεύεται από την παράμετρο τιμής σε συμβολοσειρά. |
| [String](../../system/string/) [ToString](./tostring/)() const | Μετρέπει τη τιμή που αντιπροσωπεύεται από το τρέχον αντικείμενο σε συμβολοσειρά. |
## Δείτε επίσης

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)