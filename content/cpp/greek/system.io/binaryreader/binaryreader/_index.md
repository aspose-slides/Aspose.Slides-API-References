---
title: BinaryReader()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντικείμενο της κλάσης BinaryReader που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας κωδικοποίηση UTF-8.
type: docs
weight: 1
url: /el/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) κατασκευαστής


Δημιουργεί ένα αντικείμενο της κλάσης [BinaryReader](../) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας κωδικοποίηση UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η ροή εισόδου |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) κατασκευαστής


Δημιουργεί ένα αντικείμενο της κλάσης [BinaryReader](../) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η ροή εισόδου |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Η κωδικοποίηση που θα χρησιμοποιηθεί |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) κατασκευαστής


Δημιουργεί ένα αντικείμενο της κλάσης [BinaryReader](../) που διαβάζει δεδομένα από τη συγκεκριμένη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η ροή εισόδου |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Η κωδικοποίηση που θα χρησιμοποιηθεί |
| leaveOpen | **bool** | Καθορίζει αν η ροή **input** πρέπει να παραμείνει ανοιχτή (true) μετά την απελευθέρωση του τρέχοντος αντικειμένου ή όχι (false) |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../stream/)
* Κλάση [BinaryReader](../)
* Κλάση [Encoding](../../../system.text/encoding/)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)