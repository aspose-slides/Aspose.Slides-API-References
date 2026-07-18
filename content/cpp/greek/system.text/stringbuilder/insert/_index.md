---
title: Insert()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγει τη συμβολοσειρά στη σταθερή θέση του builder.
type: docs
weight: 183
url: /el/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) μέθοδος


Εισάγει τη συμβολοσειρά σε μια σταθερή θέση του builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Θέση στην οποία θα εισαχθούν χαρακτήρες. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) για εισαγωγή. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Insert(int32_t, const String\&, int32_t) μέθοδος


Εισάγει επαναλαμβανόμενη συμβολοσειρά σε μια σταθερή θέση του builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Θέση στην οποία θα εισαχθούν χαρακτήρες. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) για εισαγωγή. |
| count | **int32_t** | Πόσες φορές να επαναληφθεί η συμβολοσειρά **value**. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Insert(int, char_t) μέθοδος


Εισάγει χαρακτήρα σε μια σταθερή θέση του builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Θέση στην οποία θα εισαχθούν χαρακτήρες. |
| ch | char_t | Χαρακτήρας για εισαγωγή. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) μέθοδος


Εισάγει χαρακτήρες σε μια σταθερή θέση του builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Θέση στην οποία θα εισαχθούν χαρακτήρες. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) για εισαγωγή τμήματος από. |
| startIndex | int | [Array](../../../system/array/) δείκτης αρχής τμήματος. |
| charCount | int | [Array](../../../system/array/) μήκος τμήματος. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Insert(int, T) μέθοδος


Εισάγει την τιμή σε μια σταθερή θέση του builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Parameter | τύπος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Θέση στην οποία θα εισαχθούν χαρακτήρες. |
| value | T | Τιμή για μορφοποίηση και εισαγωγή. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [StringBuilder](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Text](../../)
* Library [Aspose.Slides](../../../)