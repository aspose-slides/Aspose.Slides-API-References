---
title: WriteLine()
second_title: Αναφορά API Aspose.Slides για C++
description: Γράφει χαρακτήρες τερματισμού γραμμής στη ροή.
type: docs
weight: 92
url: /el/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() μέθοδος

Γράφει χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) μέθοδος

Γράφει τη συγκεκριμένη συμβολοσειρά ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Η συμβολοσειρά προς εγγραφή |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) μέθοδος

Γράφει την αναπαράσταση σε συμβολοσειρά του συγκεκριμένου αντικειμένου ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Το αντικείμενο προς εγγραφή |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) μέθοδος

Γράφει όλους τους χαρακτήρες από τον καθορισμένο πίνακα ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τους χαρακτήρες προς εγγραφή |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο χαρακτήρων UTF-16 από τον καθορισμένο πίνακα χαρακτήρων ακολουθούμενο από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τους χαρακτήρες προς εγγραφή |
| index | **int32_t** | Ένας δείκτης 0-βασισμένος στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των χαρακτήρων στο υποσύνολο προς εγγραφή· η τιμή -1 σημαίνει ότι το υποσύνολο τελειώνει στο τέλος του πίνακα **buffer** |

## StreamWriter::WriteLine(const char_t *) μέθοδος

Γράφει τη συγκεκριμένη συμβολοσειρά C ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const char_t * | Η συμβολοσειρά C προς εγγραφή |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) μέθοδος

Γράφει την αναπαράσταση σε συμβολοσειρά του συγκεκριμένου αντικειμένου ακολουθούμενη από τους χαρακτήρες τερματισμού γραμμής στη ροή.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του αντικειμένου |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Το αντικείμενο προς εγγραφή |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)