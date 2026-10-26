---
title: ToBoolean()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την καθορισμένη τιμή boolean.
type: docs
weight: 79
url: /el/system/convert/toboolean/
---
## Convert::ToBoolean(bool) μέθοδος

Επιστρέφει την καθορισμένη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) μέθοδος

Μετατρέπει τον καθορισμένο 8-bit ακέραιο χωρίς πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) μέθοδος

Μετατρέπει τον καθορισμένο 8-bit ακέραιο με πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) μέθοδος

Μετατρέπει τον καθορισμένο 16-bit ακέραιο χωρίς πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) μέθοδος

Μετατρέπει τον καθορισμένο 16-bit ακέραιο με πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) μέθοδος

Μετατρέπει τον καθορισμένο 32-bit ακέραιο χωρίς πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) μέθοδος

Μετατρέπει τον καθορισμένο 32-bit ακέραιο με πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) μέθοδος

Μετατρέπει τον καθορισμένο 64-bit ακέραιο χωρίς πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) μέθοδος

Μετατρέπει τον καθορισμένο 64-bit ακέραιο με πρόσημο σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) μέθοδος

Μετατρέπει τον καθορισμένο αριθμό float σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) μέθοδος

Μετατρέπει τον καθορισμένο αριθμό double σε ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) μέθοδος

Μετατρέπει τον καθορισμένο δεκαδικό αριθμό σε ισοδύναμη τιμή boolean.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) μέθοδος

Η μετατροπή δεν υποστηρίζεται. Πάντα πετάει InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) μέθοδος

Η μετατροπή δεν υποστηρίζεται. Πάντα πετάει InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) μέθοδος

Μετατρέπει το καθορισμένο null-string στην ισοδύναμη τιμή boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Τιμή Επιστροφής

False.

## Convert::ToBoolean(const char_t *) μέθοδος

Μετατρέπει το καθορισμένο c-string στην τιμή τύπου bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | Το c-string προς μετατροπή |

### Τιμή Επιστροφής

True αν το καθορισμένο c-string είναι ίσο με "True" και false αν είναι ίσο με "False".

## Convert::ToBoolean(const String\&) μέθοδος

Μετατρέπει το καθορισμένο string στην τιμή τύπου bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το string προς μετατροπή |

### Τιμή Επιστροφής

True αν το καθορισμένο c-string είναι ίσο με "True" και false αν το συγκεκριμένο string είναι ίσο με "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει το καθορισμένο string στην τιμή τύπου bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το string προς μετατροπή |

### Τιμή Επιστροφής

True αν το καθορισμένο c-string είναι ίσο με "True" και false αν το συγκεκριμένο string είναι ίσο με "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει την καθορισμένη τιμή σε κουτί σε ισοδύναμη τιμή boolean.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Ο shared pointer στο αντικείμενο που περιέχει την τιμή προς μετατροπή |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Η μορφή του συμβολοσειράς που θα χρησιμοποιηθεί εάν ο τύπος της τιμής σε κουτί είναι [String](../../string/) |

### Τιμή Επιστροφής

Μια τιμή boolean ισοδύναμη με την καθορισμένη τιμή σε κουτί

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Decimal](../../decimal/)
* Κλάση [DateTime](../../datetime/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [Object](../../object/)
* Δομή [Convert](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)