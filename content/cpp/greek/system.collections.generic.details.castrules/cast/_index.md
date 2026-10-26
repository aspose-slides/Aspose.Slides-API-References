---
title: Cast()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν οι τύποι προέλευσης και αποτελέσματος είναι οι ίδιοι.
type: docs
weight: 14
url: /el/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν οι τύποι προέλευσης και αποτελέσματος είναι οι ίδιοι.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος προέλευσης μπορεί να μετατραπεί στατικά στον τύπο αποτελέσματος.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν οι τύποι δεν είναι ίδιοι και ο τύπος προέλευσης δεν μπορεί να μετατραπεί στατικά στον τύπο αποτελέσματος.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος προέλευσης συσκευάζεται (boxing) σε μια κλάση [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος προέλευσης αποσυσκευάζεται (unboxing) από μια κλάση [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος προέλευσης συσκευάζεται (boxing) σε μια κλάση [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν ο τύπος προέλευσης αποσυσκευάζεται (unboxing) από μια κλάση [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## System::Collections::Generic::Details::CastRules::Cast(Source) συνάρτηση

Μετατρέπει τον τύπο προέλευσης στον τύπο αποτελέσματος. Χρησιμοποιείται όταν η μετατροπή είναι άκυρη ή η μετατροπή είναι ρητή.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος προέλευσης. |
| Result | Ο τύπος αποτελέσματος. |

### Τιμή επιστροφής

Το αποτέλεσμα της μετατροπής.

## Δείτε επίσης

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)