---
title: ExplicitCast()
second_title: Αναφορά API του Aspose.Slides για C++
description: Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν οι τύποι πηγής και αποτελέσματος είναι ίδιοι.
type: docs
weight: 2588
url: /el/system/explicitcast/
---
## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν οι τύποι πηγής και αποτελέσματος είναι ίδιοι.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν απαιτείται απλή μετατροπή τύπου παρόμοια με κατασκευαστή.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για περιτυλίγματα εξαιρέσεων.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για μετατροπή αντικειμένου σε εξαίρεση.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν τόσο η πηγή όσο και το αποτέλεσμα είναι έξυπνοι δείκτες (χωρίς ρητό SmartPtr<...> στον τύπο αποτελέσματος).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(Source) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν η ακατέργαστη δείκτης μετατρέπεται σε έξυπνο δείκτη.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | Source | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται όταν τόσο η πηγή όσο και το αποτέλεσμα είναι έξυπνοι δείκτες (με ρητό SmartPtr<...> στον τύπο αποτελέσματος).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για αποσυσκευασία αντικειμένου σε nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για δημιουργία nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για αποσυσκευασία nullable αντικειμένου.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για συσκευασία enum.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για αντιγραφή τύπων τιμής στο σωρό όταν ο τύπος τιμής πρέπει να αναφέρεται ως έξυπνος δείκτης (σε γενικές παραμέτρους περιορισμένες με τύπο διεπαφής αλλά εξειδικευμένες με δομή που υλοποιεί αυτή τη διεπαφή).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για λήψη διεπαφών από τύπους τιμής.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για κοινή συσκευασία.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για συσκευασία [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για αποσυσκευασία διεπαφών.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για κοινή αποσυσκευασία.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για μετατροπή nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::ExplicitCast(const Source\&) συνάρτηση

Κάνει μετατροπή του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας ρητή μετατροπή. Χρησιμοποιείται για μετατροπή μεταξύ πινάκων.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για μετατροπή. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## Δείτε επίσης

* Typedef [Exception](../exception/)
* Κλάση [SmartPtr](../smartptr/)
* Κλάση [BoxedValueBase](../boxedvaluebase/)
* Δομή [CastResult](../castresult/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)