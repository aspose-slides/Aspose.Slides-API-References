---
title: AsCast()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας το cast με τελεστή 'as'. Χρησιμοποιείται όταν απαιτείται απλό cast παρόμοιο με κατασκευή.
type: docs
weight: 2601
url: /el/system/ascast/
---
## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται όταν απαιτείται απλό cast παρόμοιο με κατασκευή.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται όταν ο τύπος πηγής και ο τύπος αποτελέσματος είναι οι ίδιοι.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για περιτυλίξεις εξαιρέσεων.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullptr αν δεν υπάρχει διαθέσιμη μετατροπή.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για cast αντικειμένου σε εξαίρεση.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullptr αν δεν υπάρχει διαθέσιμη μετατροπή.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται όταν τόσο η πηγή όσο και το αποτέλεσμα είναι έξυπνοι δείκτες.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullptr αν δεν υπάρχει διαθέσιμη μετατροπή.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται όταν τόσο η πηγή όσο και το αποτέλεσμα είναι έξυπνοι δείκτες (με ρητό SmartPtr<...> στον τύπο αποτελέσματος).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullptr αν δεν υπάρχει διαθέσιμη μετατροπή.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για απο-συσκευασία αντικειμένου σε nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullable κενό αν δεν υπάρχει διαθέσιμη μετατροπή.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Μη έγκυρη απο-συσκευασία σε μη-αντικειμενικό τύπο.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Επιστρέφει πάντα null.

## System::AsCast(const Source\&) συνάρτηση

Μη έγκυρη απο-συσκευασία σε μη-αντικειμενικό τύπο.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Επιστρέφει πάντα null.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για συσκευασία nullable αντικειμένου.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για συσκευασία κοινό αντικείμενο.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για συσκευασία κοινό αντικείμενο.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για απο-συσκευασία string.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για cast nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast.

## System::AsCast(const Source\&) συνάρτηση

Κάνει cast του τύπου πηγής στον τύπο αποτελέσματος χρησιμοποιώντας την μετατροπή με τελεστή 'as'. Χρησιμοποιείται για μετατροπή μεταξύ πινάκων.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### Παράμετροι προτύπου

| Parameter | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Παράμετροι

| Parameter | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) για cast. |

### Τιμή επιστροφής

Το αποτέλεσμα του cast. Επιστρέφει nullptr αν δεν υπάρχει διαθέσιμη μετατροπή για κανένα μέλος του πίνακα.

## Δείτε επίσης

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)