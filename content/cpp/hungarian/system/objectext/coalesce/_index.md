---
title: Coalesce()
second_title: Aspose.Slides C++ API referencia
description: A '??' operátor lefordítása nem nullable típusokhoz.
type: docs
weight: 170
url: /hu/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metódus


A '??' operátor lefordítása nem nullable típusokhoz.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T0 | LHS érték típusa. |
| T1 | RHS kifejezést befoglaló lambda típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T0 | LHS érték. |
| func | T1 | RHS kifejezés. |

### Visszatérési érték

Ha a LHS érték nem null, visszaadja a LHS értéket, egyébként kiszámítja a RHS kifejezést és visszaadja az eredményt.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metódus


A '??' operátor lefordítása nullable típusokhoz.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T0 | LHS érték típusa. |
| T1 | RHS kifejezést befoglaló lambda típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS érték. |
| func | T1 | RHS kifejezés. |

### Visszatérési érték

Ha a LHS érték nem null, visszaadja a LHS értéket, egyébként kiszámítja a RHS kifejezést és visszaadja az eredményt.

## Lásd még

* Osztály [ObjectExt](../)
* Osztály [Nullable](../../nullable/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)