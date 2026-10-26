---
title: StaticCast_noexcept()
second_title: Aspose.Slides C++ API Referenciája
description: Statikus átkonvertálást hajt végre a SmartPtr objektumokon.
type: docs
weight: 2549
url: /hu/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) függvény

Statikus átkonvertálást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél pointer típus. |
| TFrom | Forrás pointer típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás pointer. |

### Visszatérési érték

Az átkonvertálás eredménye, ha az engedélyezett, egyébként nullptr.

Elavult
:   A visszafelé kompatibilitás miatt megtartottuk. Használja helyette az AsCast függvényt.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) függvény

Statikus átkonvertálást hajt végre a [WeakPtr](../weakptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél pointer típus. |
| TFrom | Forrás pointer típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Forrás pointer. |

### Visszatérési érték

Az átkonvertálás eredménye, ha az engedélyezett, egyébként nullptr.

Elavult
:   A visszafelé kompatibilitás miatt megtartottuk. Használja helyette az AsCast függvényt.

## System::StaticCast_noexcept(const TFrom\&) függvény

Statikus átkonvertálást hajt végre az Exception objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | Forrás Exception típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const TFrom\& | Forrás pointer. |

### Visszatérési érték

Az átkonvertálás eredménye, ha az engedélyezett, egyébként nullptr.

Elavult
:   A visszafelé kompatibilitás miatt megtartottuk. Használja helyette az AsCast függvényt.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) függvény

Statikus átkonvertálást hajt végre az Object-eken az Exception objektumokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél Exception típus. |
| TFrom | [Object](../object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Forrás pointer. |

### Visszatérési érték

Az átkonvertálás eredménye, ha az engedélyezett, egyébként nullptr.

Elavult
:   A visszafelé kompatibilitás miatt megtartottuk. Használja helyette az AsCast függvényt.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Osztály [WeakPtr](../weakptr/)
* Osztály [Object](../object/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Struktúra [CastResult](../castresult/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)