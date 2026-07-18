---
title: Equals()
second_title: Αναφορά API Aspose.Slides για C++
description: 
type: docs
weight: 14
url: /el/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) μέθοδος




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) μέθοδος


Αντικατάσταση για κλήσεις C# [Object.Equals](../../object/equals/) που λειτουργούν για οποιονδήποτε τύπο σε C++. Υπέρφορτωση για τύπους έξυπνων δεικτών.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος πρώτου αντικειμένου. |
| T2 | Τύπος δεύτερου αντικειμένου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | Πρώτο αντικείμενο. |
| another | const T2\& | Δεύτερο αντικείμενο. |

### Τιμή επιστροφής

Αληθές εάν τα αντικείμενα θεωρούνται ίσα, ψευδές διαφορετικά.

## ObjectExt::Equals(T, const T2\&) μέθοδος


Αντικατάσταση για κλήσεις C# [Object.Equals](../../object/equals/) που λειτουργούν για οποιονδήποτε τύπο σε C++. Υπέρφορτωση για τύπους δομών.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος πρώτου αντικειμένου. |
| T2 | Τύπος δεύτερου αντικειμένου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T | Πρώτο αντικείμενο. |
| another | const T2\& | Δεύτερο αντικείμενο. |

### Τιμή επιστροφής

Αληθές εάν τα αντικείμενα θεωρούνται ίσα, ψευδές διαφορετικά.

## ObjectExt::Equals(const T\&, const T2\&) μέθοδος


Αντικατάσταση για κλήσεις C# [Object.Equals](../../object/equals/) που λειτουργούν για οποιονδήποτε τύπο σε C++. Υπέρφορτωση για τύπους αριθμητικών.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος πρώτου αντικειμένου. |
| T2 | Τύπος δεύτερου αντικειμένου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const T\& | Πρώτο αντικείμενο. |
| another | const T2\& | Δεύτερο αντικείμενο. |

### Τιμή επιστροφής

Αληθές εάν τα αντικείμενα θεωρούνται ίσα, ψευδές διαφορετικά.

## ObjectExt::Equals(const char_t(&), String) μέθοδος


Αντικατάσταση για κλήσεις C# [Object.Equals](../../object/equals/) που λειτουργούν για οποιονδήποτε τύπο σε C++. Υπέρφορτωση για κυριολεκτικό συμβολοσειράς με σύγκριση συμβολοσειράς.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| N | [String](../../string/) μέγεθος κυριολεκτικού. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) κυριολεκτικό. |
| another | [String](../../string/) | [String](../../string/). |

### Τιμή επιστροφής

Αληθές εάν οι συμβολοσειρές ταιριάζουν, ψευδές διαφορετικά.

## ObjectExt::Equals(const float\&, const float\&) μέθοδος


Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const **float**\& | Τιμή κινητής υποδιαστολής αριστερά. |
| another | const **float**\& | Τιμή κινητής υποδιαστολής δεξιά. |

### Τιμή επιστροφής

Αληθές εάν **obj** και **another** είναι και τα δύο NaN ή ίσα, ψευδές διαφορετικά.

## ObjectExt::Equals(const double\&, const double\&) μέθοδος


Προσομοιώνει σύγκριση κινητής υποδιαστολής τύπου C# όπου δύο NaN θεωρούνται ίσα, παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | const **double**\& | Τιμή κινητής υποδιαστολής αριστερά. |
| another | const **double**\& | Τιμή κινητής υποδιαστολής δεξιά. |

### Τιμή επιστροφής

Αληθές εάν **obj** και **another** είναι και τα δύο NaN ή ίσα, ψευδές διαφορετικά.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Κλάση [String](../../string/)
* Δομή [IsExceptionWrapper](../../isexceptionwrapper/)
* Δομή [IsSmartPtr](../../issmartptr/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)