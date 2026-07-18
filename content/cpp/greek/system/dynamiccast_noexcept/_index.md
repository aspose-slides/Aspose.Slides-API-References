---
title: DynamicCast_noexcept()
second_title: Aspose.Slides για την τεκμηρίωση API της C++
description: Παλιές παρωχημένες μετατροπές. Θα αφαιρεθούν σε μελλοντικές εκδόσεις.
type: docs
weight: 2484
url: /el/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) function

Παλιές παρωχημένες μετατροπές. Θα αφαιρεθούν σε μελλοντικές εκδόσεις.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Return Value

Cast result if cast is allowed or nullptr otherwise.

## Remarks

Εκτελεί δυναμική μετατροπή σε αντικείμενα Exception. Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) function

Εκτελεί δυναμική μετατροπή σε αντικείμενα [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Return Value

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) function

Εκτελεί δυναμική μετατροπή σε Objects σε αντικείμενα Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Return Value

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Κλάση [Object](../object/)
* Δομή [IsExceptionWrapper](../isexceptionwrapper/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)