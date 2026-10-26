---
title: MemoryStream()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο αντικείμενο της κλάσης MemoryStream με αρχική χωρητικότητα ίση με 0.
type: docs
weight: 1
url: /el/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() κατασκευαστής


Δημιουργεί ένα νέο αντικείμενο της κλάσης [MemoryStream](../) με αρχική χωρητικότητα ίση με 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) κατασκευαστής


Δημιουργεί ένα νέο αντικείμενο της κλάσης [MemoryStream](../) που αντιπροσωπεύει μια ροή βασισμένη σε ένα buffer μνήμης του καθορισμένου μεγέθους.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| capacity_ | int | Το μέγεθος σε bytes ενός buffer μνήμης που συνδέεται με τη ροή που αντιπροσωπεύεται από το αντικείμενο που δημιουργείται |


## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) κατασκευαστής


Δημιουργεί ένα νέο αντικείμενο της κλάσης [MemoryStream](../) που αντιπροσωπεύει μια ροή μνήμης η οποία είναι συνδεδεμένη με το καθορισμένο buffer μνήμης. Μια παράμετρος καθορίζει εάν η ροή είναι εγγράψιμη.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ένας πίνακας byte που θα χρησιμοποιηθεί ως buffer μνήμης πάνω στον οποίο θα βασίζεται η ροή που αντιπροσωπεύεται από το αντικείμενο που δημιουργείται |
| writable | **bool** | Καθορίζει εάν η ροή πρέπει να είναι εγγράψιμη |


## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) κατασκευαστής


Δημιουργεί ένα νέο αντικείμενο της κλάσης [MemoryStream](../) που αντιπροσωπεύει μια ροή μνήμης η οποία είναι συνδεδεμένη με ένα τμήμα του καθορισμένου buffer μνήμης που ξεκινά από το καθορισμένο δείκτη και περιλαμβάνει το καθορισμένο αριθμό στοιχείων. Οι παράμετροι καθορίζουν εάν η ροή είναι εγγράψιμη και εάν μπορεί να κληθεί η μέθοδος GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ένας πίνακας byte του οποίου ένα τμήμα θα χρησιμοποιηθεί ως buffer μνήμης πάνω στον οποίο θα βασίζεται η ροή που αντιπροσωπεύεται από το αντικείμενο που δημιουργείται |
| index | int | Ένας δείκτης 0-βασισμένος του στοιχείου στο **content** όπου αρχίζει το τμήμα |
| count | int | Ο αριθμός των στοιχείων του **content** που περιλαμβάνονται στο τμήμα |
| writable | **bool** | Καθορίζει εάν η ροή πρέπει να είναι εγγράψιμη |
| publiclyVisible | **bool** | Καθορίζει εάν το υποκείμενο buffer μνήμης πρέπει να είναι διαθέσιμο στον καλούντα τη μέθοδο GetByte() |


## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [MemoryStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)