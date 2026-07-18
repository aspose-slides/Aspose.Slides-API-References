---
title: WriteLine()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εξάγει το τρέχον διαχωριστικό γραμμής στο ρεύμα εξόδου που αντιπροσωπεύει το τρέχον αντικείμενο.
type: docs
weight: 27
url: /el/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() μέθοδος

Outputs the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) μέθοδος

Outputs the string representation of the specified object followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Το αντικείμενο για έξοδο |

## ConsoleOutput::WriteLine(bool) μέθοδος

Outputs the string representation of the specified bool value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **bool** | Το αντικείμενο για έξοδο |

## ConsoleOutput::WriteLine(char_t) μέθοδος

Outputs the specified character value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char_t | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(Decimal) μέθοδος

Outputs the string representation of [Decimal](../../decimal/) value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(double) μέθοδος

Outputs the string representation of double-precision floating-point value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **double** | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(int) μέθοδος

Outputs the string representation of 32-bit integer value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(int64_t) μέθοδος

Outputs the string representation of 64-bit integer value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **int64_t** | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(float) μέθοδος

Outputs the string representation of single-precision floating-point value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **float** | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(const String\&) μέθοδος

Outputs the specified string object followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το αντικείμενο συμβολοσειράς για έξοδο |

## ConsoleOutput::WriteLine(uint32_t) μέθοδος

Outputs the string representation of unsigned 32-bit integer value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint32_t** | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(uint64_t) μέθοδος

Outputs the string representation of unsigned 64-bit integer value followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **uint64_t** | Η τιμή για έξοδο |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) μέθοδος

Outputs the string representation of the specified character array followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Ο πίνακας για έξοδο |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) μέθοδος

Outputs the string representation of a range of values of the specified character array followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τις τιμές για έξοδο |
| index | **int32_t** | Ο δείκτης όπου αρχίζει η περιοχή των στοιχείων για έξοδο |
| count | **int32_t** | Ο αριθμός των στοιχείων στην περιοχή των στοιχείων για έξοδο |

## ConsoleOutput::WriteLine(const char_t *) μέθοδος

Outputs the specified c-string followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const char_t * | Το c-string για έξοδο |

## ConsoleOutput::WriteLine(const TypeInfo\&) μέθοδος

Outputs the string representation of the specified [TypeInfo](../../typeinfo/) object followed by the current line terminator to the output stream represented by the current object.

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Το [TypeInfo](../../typeinfo/) αντικείμενο για έξοδο |

## ConsoleOutput::WriteLine(const char *) μέθοδος




```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [ConsoleOutput](../)
* Κλάση [Object](../../object/)
* Κλάση [Decimal](../../decimal/)
* Κλάση [String](../../string/)
* Κλάση [TypeInfo](../../typeinfo/)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)