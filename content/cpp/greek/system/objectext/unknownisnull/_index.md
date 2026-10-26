---
title: UnknownIsNull()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει αν το αντικείμενο άγνωστου τύπου είναι nullptr. Υπερφόρτωση για μη-διανυσματικούς τύπους.
type: docs
weight: 144
url: /el/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) μέθοδος


Ελέγχει αν το αντικείμενο άγνωστου τύπου είναι nullptr. Υπερφόρτωση για μη-διανυσματικούς τύπους.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../object/) τύπου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T | [Object](../../object/) για έλεγχο. |

### Τιμή επιστροφής

Αληθές αν 'obj == nullptr' είναι αληθές, ψευδές διαφορετικά.

## ObjectExt::UnknownIsNull(T) μέθοδος


Ελέγχει αν το αντικείμενο άγνωστου τύπου είναι nullptr. Υπερφόρτωση για διανυσματικούς τύπους.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | [Object](../../object/) τύπου. |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | T | [Object](../../object/) για έλεγχο. |

### Τιμή επιστροφής

Πάντα επιστρέφει ψευδές.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)