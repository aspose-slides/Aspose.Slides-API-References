---
title: ToByte()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετατρέπει την καθορισμένη λογική τιμή σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.
type: docs
weight: 92
url: /el/system/convert/tobyte/
---
## Convert::ToByte(bool) μέθοδος

Μετατρέπει την καθορισμένη λογική τιμή σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) μέθοδος

Επιστρέφει το καθορισμένο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) μέθοδος

Μετατρέπει τον καθορισμένο 8-bit υπογεγραμμένο ακέραιο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) μέθοδος

Μετατρέπει τον καθορισμένο 16-bit ακέραιο χωρίς πρόσημο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) μέθοδος

Μετατρέπει τον καθορισμένο 16-bit υπογεγραμμένο ακέραιο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) μέθοδος

Μετατρέπει τον καθορισμένο 32-bit ακέραιο χωρίς πρόσημο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) μέθοδος

Μετατρέπει τον καθορισμένο 32-bit υπογεγραμμένο ακέραιο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) μέθοδος

Μετατρέπει τον καθορισμένο 64-bit ακέραιο χωρίς πρόσημο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) μέθοδος

Μετατρέπει τον καθορισμένο 64-bit υπογεγραμμένο ακέραιο σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) μέθοδος

Μετατρέπει τον καθορισμένο αριθμό float σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) μέθοδος

Μετατρέπει τον καθορισμένο αριθμό double σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) μέθοδος

Μετατρέπει τον καθορισμένο δεκαδικό αριθμό σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) μέθοδος

Μετατρέπει τον καθορισμένο unicode χαρακτήρα σε ισοδύναμο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) μέθοδος

Η μετατροπή δεν υποστηρίζεται. Πάντοτε αποβάλλει InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) μέθοδος

Μετατρέπει το καθορισμένο null-string στην ισοδύναμη τιμή unsigned 8-bit ακέραιου.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Τιμή Επιστροφής

Μηδέν.

## Convert::ToByte(const char_t *) μέθοδος

Μετατρέπει το καθορισμένο c-string που περιέχει την αναπαράσταση μιας αριθμητικής τιμής στην ισοδύναμη τιμή unsigned 8-bit ακέραιου.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const char_t * | Η c-string προς μετατροπή |

### Τιμή Επιστροφής

Η unsigned 8-bit ακέραια τιμή ίση με τον αριθμό που εκπροσωπείται από το καθορισμένο c-string

## Convert::ToByte(const String\&) μέθοδος

Μετατρέπει την καθορισμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή unsigned 8-bit ακέραιου.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή |

### Τιμή Επιστροφής

Η unsigned 8-bit ακέραια τιμή ίση με τον αριθμό που εκπροσωπείται από τη συγκεκριμένη συμβολοσειρά

## Convert::ToByte(const String\&, int) μέθοδος

Μετατρέπει την καθορισμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στη συγκεκριμένη βάση στην ισοδύναμη τιμή unsigned 8-bit ακέραιου.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή |
| from_base | int | Η βάση του αριθμού που εκπροσωπείται από τη συμβολοσειρά |

### Τιμή Επιστροφής

Η unsigned 8-bit ακέραια τιμή ίση με τον αριθμό που εκπροσωπείται από τη συγκεκριμένη συμβολοσειρά

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει την καθορισμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή unsigned 8-bit ακέραιου χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς |

### Τιμή Επιστροφής

Η unsigned 8-bit ακέραια τιμή ίση με τον αριθμό που εκπροσωπείται από τη συγκεκριμένη συμβολοσειρά

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει την καθορισμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού στην ισοδύναμη τιμή unsigned 8-bit ακέραιου χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός κατά bit των τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της συμβολοσειράς που αναπαριστά έναν αριθμό |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς |

### Τιμή Επιστροφής

Η unsigned 8-bit ακέραια τιμή ίση με τον αριθμό που εκπροσωπείται από τη συγκεκριμένη συμβολοσειρά

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) μέθοδος




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει την καθορισμένη συσκευασμένη τιμή σε ισοδύναμη unsigned 8-bit ακέραια τιμή.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Ο shared pointer στο αντικείμενο που συσκευάζει την τιμή προς μετατροπή |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Η μορφή συμβολοσειράς που θα χρησιμοποιηθεί αν ο τύπος της συσκευασμένης τιμής είναι [String](../../string/) |

### Τιμή Επιστροφής

Μια unsigned 8-bit ακέραια τιμή ισοδύναμη με την καθορισμένη συσκευασμένη τιμή

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)