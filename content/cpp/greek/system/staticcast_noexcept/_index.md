---
title: StaticCast_noexcept()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εκτελεί static cast σε αντικείμενα SmartPtr.
type: docs
weight: 2510
url: /el/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) συνάρτηση


Εκτελεί static cast σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Τιμή Επιστροφής

Cast result if cast is allowed or nullptr otherwise.

Αποσυρμένο
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) συνάρτηση


Εκτελεί static cast σε αντικείμενα [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Τιμή Επιστροφής

Cast result if cast is allowed or nullptr otherwise.

Αποσυρμένο
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(const TFrom\&) συνάρτηση


Εκτελεί static cast σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Τιμή Επιστροφής

Cast result if cast is allowed or nullptr otherwise.

Αποσυρμένο
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) συνάρτηση


Εκτελεί static cast σε Objects σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Τιμή Επιστροφής

Cast result if cast is allowed or nullptr otherwise.

Αποσυρμένο
:   Left for backwards compatibility. Use AsCast instead.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Κλάση [WeakPtr](../weakptr/)
* Κλάση [Object](../object/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Δομή [CastResult](../castresult/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)