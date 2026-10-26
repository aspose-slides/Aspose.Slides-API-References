---
title: operator==()
second_title: Αναφορά API για Aspose.Slides για C++
description: 
type: docs
weight: 2016
url: /el/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) συνάρτηση




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) συνάρτηση




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) συνάρτηση




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) συνάρτηση


Καθορίζει εάν το συγκεκριμένο αντικείμενο [Nullable](../nullable/) αντιπροσωπεύει μια τιμή που είναι ίση με το null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | std::nullptr_t | Μια σταθερή αναφορά σε ένα αντικείμενο [Nullable](../nullable/) για έλεγχο |

### Τιμή Επιστροφής

Αληθές εάν το συγκεκριμένο αντικείμενο αντιπροσωπεύει τιμή null, ψευδές διαφορετικά

## System::operator==(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Καθορίζει εάν η συγκεκριμένη τιμή είναι ίση με την τιμή που αντιπροσωπεύεται από το συγκεκριμένο αντικείμενο [Nullable](../nullable/) εφαρμόζοντας [operator==()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T1 | Ο τύπος της πρώτης τιμής σύγκρισης |
| T2 | Ο υποκείμενος τύπος του αντικειμένου [Nullable](../nullable/) που αντιπροσωπεύει τη δεύτερη τιμή σύγκρισης |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| some | const T1\& | Μια σταθερή αναφορά στην τιμή που θα χρησιμοποιηθεί ως η πρώτη τιμή σύγκρισης |
| other | const [Nullable](../nullable/)\<T2\>\& | Μια σταθερή αναφορά στο αντικείμενο [Nullable](../nullable/) της οποίας η αντιπροσωπευόμενη τιμή θα χρησιμοποιηθεί ως η δεύτερη τιμή σύγκρισης |

### Τιμή Επιστροφής

Αληθές εάν τα συγκρίσιμα είναι ίσα, διαφορετικά - ψευδές

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) συνάρτηση


Συγκρίνει ισότητα δύο έξυπνων δεικτών.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | Τύπος δείκτη του πρώτου δείκτη. |
| Y | Τύπος δείκτη του δεύτερου δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Πρώτος δείκτης για σύγκριση. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Δεύτερος δείκτης για σύγκριση. |

### Τιμή Επιστροφής

Αληθές εάν οι δείκτες ταιριάζουν, ψευδές διαφορετικά.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) συνάρτηση


Ελέγχει εάν ο έξυπνος δείκτης είναι null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | Τύπος δείκτη του δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | std::nullptr_t | Δείκτης για έλεγχο. |

### Τιμή Επιστροφής

Αληθές εάν ο δείκτης είναι null, ψευδές διαφορετικά.

## System::operator==(const SmartPtr\<X\>\&, const Y *) συνάρτηση


Σύγκριση ισότητας έξυπνου δείκτη με απλό (C) δείκτη.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | τύπος έξυπνου δείκτη. |
| Y | τύπος απλού δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | έξυπνος δείκτης για σύγκριση (αριστερά). |
| y | const Y * | δείκτης για σύγκριση (δεξιά). |

### Τιμή Επιστροφής

Αληθές εάν οι δείκτες ταιριάζουν, ψευδές διαφορετικά.

## System::operator==(const X *, const SmartPtr\<Y\>\&) συνάρτηση


Σύγκριση ισότητας απλού (C) δείκτη με έξυπνο δείκτη.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | τύπος απλού δείκτη. |
| Y | τύπος έξυπνου δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const X * | δείκτης για σύγκριση (δεξιά). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | έξυπνος δείκτης για σύγκριση (αριστερά). |

### Τιμή Επιστροφής

Αληθές εάν οι δείκτες ταιριάζουν, ψευδές διαφορετικά.

## System::operator==(T const\&, std::nullptr_t) συνάρτηση


Ελέγχει εάν το αντικείμενο τύπου τιμής (μεταφρασμένη δομή C#, κ.λπ.) είναι null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | T const\& | [Object](../object/) για έλεγχο. |

### Τιμή Επιστροφής

Αληθές εάν το αντικείμενο είναι null, ψευδές διαφορετικά.

## System::operator==(std::nullptr_t, T const\&) συνάρτηση


Ελέγχει εάν το αντικείμενο τύπου τιμής (μεταφρασμένη δομή C#, κ.λπ.) είναι null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος τιμής. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) για έλεγχο. |

### Τιμή Επιστροφής

Αληθές εάν το αντικείμενο είναι null, ψευδές διαφορετικά.

## System::operator==(Chars\&, const String\&) συνάρτηση


[String](../string/) σύγκριση.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Chars | [String](../string/) τύπος κυριολεκτικού. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | Chars\& | [String](../string/) κυριολεκτικό για σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) για σύγκριση. |

### Τιμή Επιστροφής

αληθές εάν οι συμβολοσειρές ταιριάζουν, ψευδές διαφορετικά.

## System::operator==(T\&, const String\&) συνάρτηση


[String](../string/) σύγκριση.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [String](../string/) τύπος δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | T\& | [String](../string/) δείκτης για σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) για σύγκριση. |

### Τιμή Επιστροφής

αληθές εάν οι συμβολοσειρές ταιριάζουν, ψευδές διαφορετικά.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) συνάρτηση


[Object](../object/) και σύγκριση συμβολοσειράς.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) για μετατροπή σε συμβολοσειρά και σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) για σύγκριση. |

### Τιμή Επιστροφής

αληθές εάν η αναπαράσταση αντικειμένου ως συμβολοσειρά ισούται με τη συμβολοσειρά, ψευδές διαφορετικά.

## System::operator==(std::nullptr_t, const String\&) συνάρτηση


Ελέγχει εάν η συμβολοσειρά είναι null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) για έλεγχο. |

### Τιμή Επιστροφής

αληθές εάν η συμβολοσειρά είναι null, ψευδές διαφορετικά.

## System::operator==(std::nullptr_t, TimeSpan) συνάρτηση




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) συνάρτηση


Καθορίζει εάν τα URIs που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο είναι ίσα.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Το πρώτο αντικείμενο [Uri](../uri/) για σύγκριση |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Το δεύτερο αντικείμενο [Uri](../uri/) για σύγκριση |

### Τιμή Επιστροφής

Αληθές εάν τα URIs είναι ίσα, διαφορετικά - ψευδές

## Δείτε επίσης

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)