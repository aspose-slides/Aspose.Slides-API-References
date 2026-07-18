---
title: Unbox()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποσυσκευάζει τύπους τιμής μετά τη μετατροπή σε Object. Υλοποίηση για τύπους enum.
type: docs
weight: 53
url: /el/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) μέθοδος

Αποσυσκευάζει τύπους τιμής μετά τη μετατροπή σε [Object](../../object/). Υλοποίηση για τύπους enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Enum](../../enum/) τύπο. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) για αποσυσκευασία. |

### Τιμή Επιστροφής

[Enum](../../enum/) τιμή.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) μέθοδος

Αποσυσκευάζει τύπους τιμής μετά τη μετατροπή σε [Object](../../object/). Υλοποίηση για μη-enum & μη-nullable τύπους.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπο τιμής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) για αποσυσκευασία. |

### Τιμή Επιστροφής

Αποσυσκευασμένη τιμή.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) μέθοδος

Αποσυσκευάζει τύπους τιμής μετά τη μετατροπή σε [Object](../../object/). Υλοποίηση για μη-enum & μη-nullable τύπους.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπο τιμής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) για αποσυσκευασία. |

### Τιμή Επιστροφής

Αποσυσκευασμένη τιμή.

## ObjectExt::Unbox(E) μέθοδος

Αποσυσκευάζει τύπους enum σε ακέραιο.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος ακέραιου προορισμού. |
| E | Τύπος enum προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| e | E | Τιμή για αποσυσκευασία. |

### Τιμή Επιστροφής

Ακέραια αναπαράσταση του enum.

## ObjectExt::Unbox(E) μέθοδος

Μετατρέπει τύπους enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος enum προορισμού. |
| E | Τύπος enum προέλευσης. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| e | E | Τιμή για αποσυσκευασία. |

### Τιμή Επιστροφής

Μετατρεπόμενη τιμή enum.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) μέθοδος

Αποσυσκευάζει τιμές συμβολοσειράς.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) για αποσυσκευασία |

### Τιμή Επιστροφής

[String](../../string/) αναπαράσταση της συσκευασμένης συμβολοσειράς, μπορεί να είναι null εάν η συσκευασμένη συμβολοσειρά ήταν null.

## Δείτε επίσης

* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [Object](../../object/)
* Κλάση [ObjectExt](../)
* Κλάση [String](../../string/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)