---
title: operator!=()
second_title: Αναφορά API Aspose.Slides για C++
description: 
type: docs
weight: 2029
url: /el/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) συνάρτηση




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) συνάρτηση




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) συνάρτηση




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) συνάρτηση


Καθορίζει αν το καθορισμένο [Nullable](../nullable/) αντικείμενο αντιπροσωπεύει μια τιμή που δεν είναι ίση με το null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | std::nullptr_t | Μία σταθερή αναφορά σε ένα αντικείμενο [Nullable](../nullable/) για δοκιμή |

### Τιμή Επιστροφής

Αληθές εάν το καθορισμένο αντικείμενο αντιπροσωπεύει μη-μηδενική τιμή, ψευδές διαφορετικά

## System::operator!=(const T1\&, const Nullable\<T2\>\&) συνάρτηση


Καθορίζει αν η καθορισμένη τιμή δεν είναι ίση με την τιμή που αντιπροσωπεύεται από το καθορισμένο [Nullable](../nullable/) αντικείμενο εφαρμόζοντας [operator!=()](./) σε αυτές τις τιμές.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Παράμετροι Προτύπου

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

Αληθές εάν οι τιμές σύγκρισης δεν είναι ίσες, διαφορετικά ψευδές

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) συνάρτηση


Συγκρίνει αν δύο έξυπνοι δείκτες δεν είναι ίσοι.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | Τύπος του δείκτη που δείχνει |
| Y | Τύπος του δείκτη που δείχνει |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Πρώτος δείκτης προς σύγκριση. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Δεύτερος δείκτης προς σύγκριση. |

### Τιμή Επιστροφής

Ψευδές εάν οι δείκτες ταιριάζουν, αληθές διαφορετικά.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) συνάρτηση


Ελέγχει αν ο έξυπνος δείκτης δεν είναι null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | Τύπος του δείκτη που δείχνει. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Δείκτης προς έλεγχο. |

### Τιμή Επιστροφής

Ψευδές εάν ο δείκτης είναι null, αληθές διαφορετικά.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) συνάρτηση


Ελέγχει αν ο έξυπνος δείκτης δεν είναι null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | Τύπος του δείκτη που δείχνει. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | std::nullptr_t | Δείκτης προς έλεγχο. |

### Τιμή Επιστροφής

Ψευδές εάν ο δείκτης είναι null, αληθές διαφορετικά.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) συνάρτηση


Σύγκριση ανισότητας του έξυπνου δείκτη έναντι απλού (C) δείκτη.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | τύπος του έξυπνου δείκτη. |
| Y | τύπος απλού δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | έξυπνος δείκτης για σύγκριση (αριστερά). |
| y | const Y * | δείκτης για σύγκριση (δεξιά). |

### Τιμή Επιστροφής

Ψευδές εάν οι δείκτες ταιριάζουν, αληθές διαφορετικά.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) συνάρτηση


Σύγκριση ανισότητας έξυπνου δείκτη έναντι απλού (C) δείκτη.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| X | τύπος απλού δείκτη. |
| Y | τύπος έξυπνου δείκτη. |

### Παράμετρος

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | const X * | δείκτης για σύγκριση (δεξιά). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | έξυπνος δείκτης για σύγκριση (αριστερά). |

### Τιμή Επιστροφής

Ψευδές εάν οι δείκτες ταιριάζουν, αληθές διαφορετικά.

## System::operator!=(Chars\&, const String\&) συνάρτηση


[String](../string/) σύγκριση.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Chars | [String](../string/) τύπου κυριολεκτικού. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | Chars\& | [String](../string/) κυριολεκτικό προς σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) προς σύγκριση. |

### Τιμή Επιστροφής

ψευδές εάν τα strings ταιριάζουν, αληθές διαφορετικά.

## System::operator!=(T\&, const String\&) συνάρτηση


[String](../string/) σύγκριση.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Παράμετροι Προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [String](../string/) τύπος δείκτη. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | T\& | [String](../string/) δείκτης προς σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) προς σύγκριση. |

### Τιμή Επιστροφής

ψευδές εάν τα strings ταιριάζουν, αληθές διαφορετικά.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) συνάρτηση


[Object](../object/) και σύγκριση string.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) για μετατροπή σε string και σύγκριση. |
| right | const [String](../string/)\& | [String](../string/) προς σύγκριση. |

### Τιμή Επιστροφής

ψευδές εάν η αναπαράσταση του αντικειμένου σε string ισούται με το string, αληθές διαφορετικά.

## System::operator!=(std::nullptr_t, const String\&) συνάρτηση


Ελέγχει αν το string είναι null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) για έλεγχο. |

### Τιμή Επιστροφής

ψευδές εάν το string είναι null, αληθές διαφορετικά.

## System::operator!=(std::nullptr_t, TimeSpan) συνάρτηση




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) συνάρτηση


Καθορίζει αν οι URI που αντιπροσωπεύονται από το τρέχον και το καθορισμένο αντικείμενο δεν είναι ίσοι.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Το πρώτο [Uri](../uri/) αντικείμενο προς σύγκριση |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Το δεύτερο [Uri](../uri/) αντικείμενο προς σύγκριση |

### Τιμή Επιστροφής

Αληθές εάν οι URI δεν είναι ίσοι, διαφορετικά ψευδές

## Δείτε Επίσης

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