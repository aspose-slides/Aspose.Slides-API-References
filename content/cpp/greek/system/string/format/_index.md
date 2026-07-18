---
title: Format()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαμορφώνει συμβολοσειρά σε στυλ C#.
type: docs
weight: 885
url: /el/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) μέθοδος


Διαμορφώνει συμβολοσειρά σε στυλ C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Args | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Παρόχης μορφοποίησης που χρησιμοποιείται για τη μετατροπή των ορισμάτων σε συμβολοσειρές. |
| format | const [String](../)\& | Συμβολοσειρά μορφοποίησης. |
| args | const Args\&... | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) μέθοδος


Διαμορφώνει συμβολοσειρά σε στυλ C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Args | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | std::nullptr_t | Συμβολοσειρά μορφοποίησης. |
| args | const [String](../)\& | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) μέθοδος


Διαμορφώνει συμβολοσειρά σε στυλ C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Args | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | std::nullptr_t | Συμβολοσειρά μορφοποίησης. |
| args | const char16_t(&) | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

## String::Format(const String\&, const Args\&...) μέθοδος


Διαμορφώνει συμβολοσειρά σε στυλ C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Args | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../)\& | Συμβολοσειρά μορφοποίησης. |
| args | const Args\&... | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) μέθοδος


Διαμορφώνει συμβολοσειρά σε στυλ C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | const [String](../)\& | Συμβολοσειρά μορφοποίησης. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Ορίσματα για τη διαμόρφωση της συμβολοσειράς. |

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [String](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)