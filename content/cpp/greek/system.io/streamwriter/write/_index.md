---
title: Write()
second_title: Aspose.Slides για C++ Αναφορά API
description: Γράφει τον καθορισμένο χαρακτήρα στη ροή.
type: docs
weight: 79
url: /el/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) μέθοδος

Γράφει τον καθορισμένο χαρακτήρα στη ροή.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | The character to write |

## StreamWriter::Write(const String\&) μέθοδος

Γράφει τη καθορισμένη συμβολοσειρά στη ροή.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## StreamWriter::Write(const SharedPtr\<Object\>\&) μέθοδος

Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου στη ροή.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The object to write |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) μέθοδος

Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα στη ροή.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων στη ροή.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** όπου ξεκινά το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των χαρακτήρων στο υποσύνολο προς εγγραφή· -1 καθορίζει ότι το υποσύνολο τελειώνει όταν τελειώνει ο πίνακας **buffer** |

## StreamWriter::Write(const char_t *) μέθοδος

Γράφει τη συγκεκριμένη c-string στη ροή.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const char_t * | Η c-string προς εγγραφή |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) μέθοδος

Γράφει την αναπαράσταση συμβολοσειράς του καθορισμένου αντικειμένου στη ροή.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Ο τύπος του αντικειμένου |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Το αντικείμενο προς εγγραφή |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [StreamWriter](../)
* Κλάση [String](../../../system/string/)
* Κλάση [Object](../../../system/object/)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)