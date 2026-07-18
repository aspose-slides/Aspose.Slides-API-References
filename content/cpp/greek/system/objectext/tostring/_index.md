---
title: ToString()
second_title: Aspose.Slides για C++ API Reference
description: Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.
type: docs
weight: 27
url: /el/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) κυριολεκτικό για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Nullable](../../nullable/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) αντικείμενο για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(const T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Enum](../../enum/) τύπος. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) τιμή για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(const T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος δείκτη έξυπνου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) τιμή για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος δείκτη έξυπνου ή [ExceptionWrapper](../../exceptionwrapper/). |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T\& | Δείκτης έξυπνος ή [ExceptionWrapper](../../exceptionwrapper/) για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος βαθμωτού. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T\& | Τιμή βαθμωτού για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(T\&&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος βαθμωτού. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T\&& | Τιμή βαθμωτού για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος δομής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T\& | Τιμή δομής για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(const T\&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος δομής. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | Τιμή δομής για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## ObjectExt::ToString(T\&&) μέθοδος

Αντικατάσταση της μεθόδου C# ToString για λειτουργία με οποιονδήποτε τύπο C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος βαθμωτού. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T\&& | Τιμή βαθμωτού για μετατροπή σε συμβολοσειρά. |

### Τιμή επιστροφής

[String](../../string/) αναπαράσταση του **obj**.

## Δείτε επίσης

* Κλάση [String](../../string/)
* Κλάση [ObjectExt](../)
* Κλάση [Nullable](../../nullable/)
* Δομή [IsSmartPtr](../../issmartptr/)
* Δομή [IsExceptionWrapper](../../isexceptionwrapper/)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)