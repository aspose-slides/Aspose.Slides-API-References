---
title: Guid()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει ένα GUID που αποτελείται αποκλειστικά από μηδενικά.
type: docs
weight: 1
url: /el/system/guid/guid/
---
## Guid::Guid() κατασκευαστής

Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει ένα GUID που αποτελείται αποκλειστικά από μηδενικά.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει ένα GUID που ορίζεται ως πίνακας ακεραίων 8-bit χωρίς πρόσημο.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ένας πίνακας byte που περιέχει ξεχωριστά byte του GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει ένα GUID που ορίζεται ως προβολή πίνακα ακεραίων 8-bit χωρίς πρόσημο.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Ένας πίνακας byte που περιέχει ξεχωριστά byte του GUID |

## Guid::Guid(const String\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει ένα GUID που ορίζεται ως συμβολοσειρά.

```cpp
System::Guid::Guid(const String &g)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | const [String](../../string/)\& | Η συμβολοσειρά που αντιπροσωπεύει το GUID που θα χρησιμοποιηθεί για τη δημιουργία του αντικειμένου |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [Guid](../) από τα συγκεκριμένα στοιχεία του GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 του GUID |
| b | **int16_t** | Bits 32-47 του GUID |
| c | **int16_t** | Bits 48-63 του GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Ένας πίνακας byte που περιέχει τα bits 64-127 του GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [Guid](../) από τα συγκεκριμένα στοιχεία του GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 του GUID |
| b | **int16_t** | Bits 32-47 του GUID |
| c | **int16_t** | Bits 48-63 του GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Μια προβολή πίνακα byte που περιέχει τα bits 64-127 του GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [Guid](../) από τις συγκεκριμένες ακεραίες χωρίς πρόσημο και τα byte.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 του GUID |
| b | **int16_t** | Bits 32-47 του GUID |
| c | **int16_t** | Bits 48-63 του GUID |
| d | **uint8_t** | Bits 64-71 του GUID |
| e | **uint8_t** | Bits 72-79 του GUID |
| f | **uint8_t** | Bits 80-87 του GUID |
| g | **uint8_t** | Bits 88-95 του GUID |
| h | **uint8_t** | Bits 96-103 του GUID |
| i | **uint8_t** | Bits 104-111 του GUID |
| j | **uint8_t** | Bits 112-119 του GUID |
| k | **uint8_t** | Bits 120-127 του GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) κατασκευαστής

Δημιουργεί μια παρουσία της κλάσης [Guid](../) από τις συγκεκριμένες ακεραίες χωρίς πρόσημο και τα byte.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 του GUID |
| b | **uint16_t** | Bits 32-47 του GUID |
| c | **uint16_t** | Bits 48-63 του GUID |
| d | **uint8_t** | Bits 64-71 του GUID |
| e | **uint8_t** | Bits 72-79 του GUID |
| f | **uint8_t** | Bits 80-87 του GUID |
| g | **uint8_t** | Bits 88-95 του GUID |
| h | **uint8_t** | Bits 96-103 του GUID |
| i | **uint8_t** | Bits 104-111 του GUID |
| j | **uint8_t** | Bits 112-119 του GUID |
| k | **uint8_t** | Bits 120-127 του GUID |

## Guid::Guid(const Guid\&) κατασκευαστής

Δημιουργεί ένα αντικείμενο που αντιπροσωπεύει το ίδιο GUID με το καθορισμένο αντικείμενο.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | const [Guid](../)\& | Το αντικείμενο [Guid](../) από το οποίο θα αντιγραφεί η τιμή του GUID |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [Guid](../)
* Κλάση [String](../../string/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)