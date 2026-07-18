---
title: PrintTo()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.
type: docs
weight: 2120
url: /el/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) συνάρτηση

Γράφει την τιμή που αντιπροσωπεύεται από το καθορισμένο αντικείμενο στη καθορισμένη ροή εξόδου.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Το [Decimal](../decimal/) αντικείμενο για εκτύπωση στο ρεύμα |
| os | ::std::ostream * | Το ρεύμα για εκτύπωση του καθορισμένου αντικειμένου |

## System::PrintTo(const Details_Exception\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) συνάρτηση

Εκτυπώνει το κείμενο στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [System::String](../string/)\& | για εκτύπωση. |
| os | std::ostream * | στόχο ostream. |

## System::PrintTo(TimeSpan, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) συνάρτηση

Εκτυπώνει την τιμή στο ostream. Κυρίως χρησιμοποιείται για αποσφαλμάτωση.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Δείτε επίσης

* Κλάση [DateTime](../datetime/)
* Κλάση [DateTimeOffset](../datetimeoffset/)
* Κλάση [Decimal](../decimal/)
* Κλάση [Details_Exception](../details_exception/)
* Κλάση [ExceptionWrapper](../exceptionwrapper/)
* Κλάση [Guid](../guid/)
* Κλάση [Nullable](../nullable/)
* Κλάση [Object](../object/)
* Κλάση [SmartPtr](../smartptr/)
* Κλάση [String](../string/)
* Κλάση [TimeSpan](../timespan/)
* Κλάση [WeakPtr](../weakptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)