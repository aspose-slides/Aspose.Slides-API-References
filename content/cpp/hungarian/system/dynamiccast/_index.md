---
title: DynamicCast()
second_title: Aspose.Slides C++ API referencia
description: Dinamikus castot hajt végre Exception objektumokon.
type: docs
weight: 2536
url: /hu/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) függvény

Dinamikus leképezést hajt végre Exception objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | Forrás Exception típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const TFrom\& | Forrás mutató. |

### Visszatérési érték

A cast eredménye, ha a cast megengedett.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) függvény

Dinamikus leképezést hajt végre [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél pointee típus. |
| TFrom | Forrás pointee típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás mutató. |

### Visszatérési érték

A cast eredménye, ha a cast megengedett.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(SmartPtr\<TFrom\>) függvény

Kicsomagolja a becsomagolt enumot cast segítségével.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél enum típus. |
| TFrom | Forrás pointee típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Mutató az objektumra, amelyből az adatot kicsomagolni kell. |

### Visszatérési érték

Kicsomagolt enum érték.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(std::nullptr_t) függvény

Dinamikus castot hajt végre null objektumokon.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél pointee típus. |

### Visszatérési érték

nullptr.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(TFrom\&) függvény

Dinamikus castot hajt végre nem-pointer objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél típus. |
| TFrom | Forrás típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | TFrom\& | Forrás objektum. |

### Visszatérési érték

Cast eredmény.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(SmartPtr\<TFrom\>) függvény

Dinamikus castot hajt végre Objects objektumokon Exception objektumokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | [Object](../object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Forrás mutató. |

### Visszatérési érték

A cast eredménye, ha a cast megengedett.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## System::DynamicCast(TFrom) függvény

Dinamikus castot hajt végre az IntPtr-ről mutatóra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél típus. |
| TFrom | Forrás típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | TFrom | Forrás IntPtr érték. |

### Visszatérési érték

Cast eredmény.

Elavult
:   Megmarad a visszafelé kompatibilitás érdekében. Használd az ExplicitCast helyett.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Osztály [Object](../object/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Struktúra [CastResult](../castresult/)
* Struktúra [IsSmartPtr](../issmartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)