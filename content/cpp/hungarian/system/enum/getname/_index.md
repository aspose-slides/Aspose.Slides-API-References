---
title: GetName()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a megadott értékkel rendelkező enumerációs konstans nevét.
type: docs
weight: 40
url: /hu/system/enum/getname/
---
## Enum::GetName(T) metódus


Visszaadja a megadott értékkel rendelkező enumerációs konstans nevét.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | Az enum konstans értéke, amelynek a nevét vissza kell adni |

### Visszatérési érték

A megadott enum konstans neve

## Lásd még

* Typedef [UnderlyingType](../underlyingtype/)
* Osztály [String](../../string/)
* Struktúra [Enum](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)