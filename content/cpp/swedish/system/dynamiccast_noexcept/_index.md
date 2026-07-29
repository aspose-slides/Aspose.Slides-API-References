---
title: DynamicCast_noexcept()
second_title: Aspose.Slides för C++ API-referens
description: Gamla föråldrade kast. Kommer att tas bort i framtida versioner.
type: docs
weight: 2523
url: /sv/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) funktion


Gamla föråldrade kast. Kommer att tas bort i framtida versioner.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målexception typ. |
| TFrom | Käll-Exception typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const TFrom\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet annars nullptr.

## Anmärkningar


Utför dynamisk cast på Exception-objekt. Avskriven
:   Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) funktion


Utför dynamisk cast på [SmartPtr](../smartptr/) objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målpåpekad typ. |
| TFrom | Källpåpekad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet annars nullptr.

Avskriven
:   Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) funktion


Utför dynamisk cast på objekt till Exception-objekt.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TTo | Målexception typ. |
| TFrom | [Object](../object/) typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Källpekare. |

### Returvärde

Kastresultat om kastet är tillåtet annars nullptr.

Avskriven
:   Lämnad för bakåtkompatibilitet. Använd AsCast istället.

## Se även

* Klass [SmartPtr](../smartptr/)
* Klass [Object](../object/)
* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)