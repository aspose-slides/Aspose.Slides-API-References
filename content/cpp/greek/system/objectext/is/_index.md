---
title: Is()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Υλοποιεί τη μετάφραση του τελεστή 'is'. Ειδική εξειδίκευση για τύπους που μπορούν να τοποθετηθούν σε κουτί (τιμής) που είναι ακριβώς όπως είναι.
type: docs
weight: 92
url: /el/system/objectext/is/
---
## ObjectExt::Is(const T&) μέθοδος

Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T& | [Object](../../object/) για δοκιμή του τελεστή 'is'. Αγνοείται. |

### Τιμή Επιστροφής

Πάντα αληθές

## ObjectExt::Is(const U&) μέθοδος

Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const U& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const U&) μέθοδος

Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const U& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const Object&) μέθοδος

Implements 'is' operator translation. Specialization for value types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [Object](../../object/)& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const Object&) μέθοδος

Implements 'is' operator translation. Specialization for unconvertible types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [Object](../../object/)& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Πάντα επιστρέφει ψευδές καθώς οι τύποι δεν είναι μετατρέψιμοι.

## ObjectExt::Is(const SmartPtr\<U>\&) μέθοδος

Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<U>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const ExceptionWrapper\<U>\&) μέθοδος

Implements 'is' operator translation. Specialization for exception wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)<U>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const SmartPtr\<Object>\&) μέθοδος

Implements 'is' operator translation. Specialization for nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<[Object](../../object/)>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const SmartPtr\<Object>\&) μέθοδος

Implements 'is' operator translation. Specialization for boxable types with == operator defined.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<[Object](../../object/)>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const SmartPtr\<Object>\&) μέθοδος

Implements 'is' operator translation. Specialization for boxable types without defined ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<[Object](../../object/)>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const SmartPtr\<V>\&) μέθοδος

Implements 'is' operator translation. Specialization value types boxed to interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |
| V | Type of the pointed object. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<V>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const SmartPtr\<U>\&) μέθοδος

Implements 'is' operator translation. Specialization for enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)<U>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const WeakPtr\<U>\&) μέθοδος

Implements 'is' operator translation. Specialization for enum types vs weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)<U>& | [Object](../../object/) για δοκιμή του τελεστή 'is'. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const Nullable\<U>\&) μέθοδος

Implements 'is' operator translation. Specialization for [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)<U>& | [Nullable](../../nullable/) τύπο. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(const char16_t *) μέθοδος

Implements 'is' operator translation. Specialization for string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) κυριολεκτικό. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## ObjectExt::Is(int32_t) μέθοδος

Implements 'is' operator translation. Specialization for integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Target type. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | **int32_t** | ακέραιο κυριολεκτικό. |

### Τιμή Επιστροφής

Αληθές εάν το 'is' επιστρέφει αληθές, ψευδές διαφορετικά.

## See Also

* Κλάση [ObjectExt](../)
* Κλάση [Object](../../object/)
* Κλάση [SmartPtr](../../smartptr/)
* Κλάση [ExceptionWrapper](../../exceptionwrapper/)
* Κλάση [WeakPtr](../../weakptr/)
* Κλάση [Nullable](../../nullable/)
* Δομή [IsBoxable](../../isboxable/)
* Δομή [IsSmartPtr](../../issmartptr/)
* Δομή [IsExceptionWrapper](../../isexceptionwrapper/)
* Δομή [IsNullable](../../isnullable/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)