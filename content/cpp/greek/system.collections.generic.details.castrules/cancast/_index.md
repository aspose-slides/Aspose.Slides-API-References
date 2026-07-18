---
title: CanCast()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει τη δυνατότητα μετατροπής.
type: docs
weight: 40
url: /el/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Αληθές όταν ένα μη nullptr τιμή επιστρέφεται μετά τη μετατροπή, διαφορετικά ψευδές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Αληθές όταν ένα μη nullptr τιμή επιστρέφεται μετά τη μετατροπή, διαφορετικά ψευδές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Αληθές όταν ένα μη nullptr τιμή επιστρέφεται μετά τη μετατροπή, διαφορετικά ψευδές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Επιστρέφει πάντα αληθές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Αληθές όταν ένα μη nullptr τιμή επιστρέφεται μετά τη μετατροπή, διαφορετικά ψευδές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Επιστρέφει πάντα αληθές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Αληθές εάν η ενέργεια μετατροπής ολοκληρώθηκε επιτυχώς, διαφορετικά ψευδές.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function

Ελέγχει τη δυνατότητα μετατροπής.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### Template parameters

| Παράμετρος | Περιγραφή |
| --- | --- |
| Source | Ο τύπος πηγής. |
| Result | Ο τύπος αποτελέσματος. |

### Return Value

Επιστρέφει πάντα ψευδές.

## See Also

* Δομή [CastType](../casttype/)
* Χώρος ονομάτων [System::Collections::Generic::Details::CastRules](../)
* Βιβλιοθήκη [Aspose.Slides](../../)