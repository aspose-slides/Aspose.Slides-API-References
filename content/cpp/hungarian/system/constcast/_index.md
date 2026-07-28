---
title: ConstCast()
second_title: Aspose.Slides for C++ API Referencia
description: Az elavult átalakítások vége.
type: docs
weight: 2575
url: /hu/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) függvény


Elavult átalakítások vége.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TTo | Cél mutatott típus. |
| TFrom | Forrás mutatott típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Forrás mutató. |

### Visszatérési érték

Az átalakítás eredménye, ha az átalakítás megengedett, egyébként nullptr.

## Megjegyzés


Konstans átalakítást hajt végre a [SmartPtr](../smartptr/) objektumokon. 
## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Struktúra [CastResult](../castresult/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)