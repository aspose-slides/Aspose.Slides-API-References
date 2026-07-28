---
title: GetDescription()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a megadott értékkel rendelkező enumerációs állandó nevét.
type: docs
weight: 53
url: /hu/system/enum/getdescription/
---
## Enum::GetDescription(T) metódus


Visszaadja a megadott értékkel rendelkező enumerációs állandó nevét.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T | Az enumerációs állandó értéke, amelynek a nevét vissza kell adni |

### Visszatérési érték

A megadott enumerációs állandó neve

## Lásd még

* Typedef [UnderlyingType](../underlyingtype/)
* Osztály [String](../../string/)
* Struktúra [Enum](../)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)