---
title: DynamicCast_noexcept()
second_title: Aspose.Slides a C++ API referencia
description: Régi elavult átalakítások. A jövőbeli verziókban eltávolításra kerülnek.
type: docs
weight: 2523
url: /hu/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) függvény

Régi elavult átalakítások. A jövőbeli verziókban eltávolításra kerülnek.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél kivétel típusa. |
| TFrom | Forrás kivétel típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const TFrom\& | Forrás mutató. |

### Visszatérési érték

Az átalakítás eredménye, ha az átalakítás engedélyezett, különben nullptr.

## Megjegyzés

Dinamikus átalakítást hajt végre Kivétel objektumokon.  
Elavult
:   Hátrafelé kompatibilitás miatt maradt. Használja helyette az AsCast-et.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) függvény

Dinamikus átalakítást hajt végre a [SmartPtr](../smartptr/) objektumokon.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Forrás mutató. |

### Visszatérési érték

Az átalakítás eredménye, ha az átalakítás engedélyezett, különben nullptr.

Elavult
:   Hátrafelé kompatibilitás miatt maradt. Használja helyette az AsCast-et.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) függvény

Dinamikus átalakítást hajt végre az Objektumokból Kivétel objektumokra.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél kivétel típusa. |
| TFrom | [Object](../object/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Forrás mutató. |

### Visszatérési érték

Az átalakítás eredménye, ha az átalakítás engedélyezett, különben nullptr.

Elavult
:   Hátrafelé kompatibilitás miatt maradt. Használja helyette az AsCast-et.

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Osztály [Object](../object/)
* Struktúra [IsExceptionWrapper](../isexceptionwrapper/)
* Névtere [System](../)
* Könyvtár [Aspose.Slides](../../)