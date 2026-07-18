---
title: Append()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Προσθέτει χαρακτήρα στον builder.
type: docs
weight: 118
url: /el/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) μέθοδος

Προσθέτει χαρακτήρα στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | char_t | Τιμή χαρακτήρα. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(char_t, int) μέθοδος

Προσθέτει χαρακτήρες στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | char_t | Τιμή χαρακτήρα. |
| count | int | Πόσες φορές να επαναληφθεί ο εισαχθέν χαρακτήρας. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) μέθοδος

Προσθέτει πίνακα χαρακτήρων στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Χαρακτήρες για προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) μέθοδος

Προσθέτει τμήμα πίνακα χαρακτήρων στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Χαρακτήρες για προσθήκη. |
| startIndex | int | Δείκτης έναρξης τμήματος. |
| charCount | int | Μήκος τμήματος. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const String\&) μέθοδος

Προσθέτει συμβολοσειρά στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) για προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const String\&, int, int) μέθοδος

Προσθέτει τμήμα συμβολοσειράς στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) για προσθήκη. |
| startIndex | int | Δείκτης έναρξης τμήματος. |
| charCount | int | Μήκος τμήματος. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const SharedPtr\<T\>\&) μέθοδος

Προσθέτει την αναπαράσταση συμβολοσειράς του αντικειμένου στον builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος [Object](../../../system/object/). |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) μέθοδος

Προσθέτει το περιεχόμενο του builder σε builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder από τον οποίο θα προστεθεί το περιεχόμενο. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(float) μέθοδος

Προσθέτει τιμή κινητής υποδιαστολής στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| f | **float** | Τιμή για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(double) μέθοδος

Προσθέτει τιμή κινητής υποδιαστολής στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| df | **double** | Τιμή για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(int) μέθοδος

Προσθέτει ακέραια τιμή στον builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| i | int | Τιμή για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(T) μέθοδος

Προσθέτει αριθμητική τιμή στον builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Αριθμητικός τύπος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T | Τιμή για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## StringBuilder::Append(E) μέθοδος

Προσθέτει την αναπαράσταση συμβολοσειράς της τιμής enum στον builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| E | Τύπος [Enum](../../../system/enum/). |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| e | E | Τιμή για σειριοποίηση και προσθήκη. |

### Τιμή Επιστροφής

Αυτός ο δείκτης.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [StringBuilder](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)