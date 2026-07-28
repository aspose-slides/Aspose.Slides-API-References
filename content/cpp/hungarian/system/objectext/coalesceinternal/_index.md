---
title: CoalesceInternal()
second_title: Aspose.Slides C++ API referencia
description: A '??' operátor nem nullable típusokra való fordításának megvalósítása. Túlterhelés arra az esetre, ha az RT2 konvertálható az RT1-be.
type: docs
weight: 157
url: /hu/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metódus


Nem nullable típusok esetén a '??' operátor implementációja. Túlterhelés arra az esetre, amikor az RT2 konvertálható az RT1-be.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T0 | LHS érték típusa. |
| T1 | A jobboldali kifejezést befoglaló lambda típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | RT1 | LHS érték. |
| func | F | Jobboldali kifejezés. |

### Visszatérési érték

Ha a LHS érték nem null, visszaadja a LHS-t, egyébként kiszámítja a jobboldali kifejezést és visszaadja az eredményt.

## Lásd még

* Osztály [ObjectExt](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)