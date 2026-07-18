---
title: ComputeHash()
second_title: Aspose.Slides για Αναφορά API C++
description: Υπολογίζει hash του buffer.
type: docs
weight: 14
url: /el/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) μέθοδος

Υπολογίζει hash του buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Πηγαίος buffer. |

### Τιμή Επιστροφής

Υπολογισμένη τιμή hash.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) μέθοδος

Υπολογίζει hash τμήματος buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Πηγαίος buffer. |
| offset | int | Μετατόπιση στο πηγαίο buffer. |
| count | int | Αριθμός byte που θα χρησιμοποιηθούν από το πηγαίο buffer. |

### Τιμή Επιστροφής

Υπολογισμένη τιμή hash.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) μέθοδος

Διαβάζει τη ροή μέχρι το τέλος και υπολογίζει το hash για τα διαβασμένα δεδομένα.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Ροή για ανάγνωση δεδομένων. |

### Τιμή Επιστροφής

Υπολογισμένη τιμή hash για ολόκληρα τα δεδομένα της ροής.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [HashAlgorithm](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)