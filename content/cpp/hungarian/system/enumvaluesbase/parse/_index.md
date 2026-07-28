---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy objektumot, amely a megadott enumerációs típusú enumerációs állandó értékét képviseli a megadott névvel.
type: docs
weight: 27
url: /hu/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metódus


Visszaad egy objektumot, amely a megadott enumerációs típusú enumerációs állandó értékét képviseli a megadott névvel.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | A [TypeInfo](../../typeinfo/) objektum, amely a visszaadandó enumerációs érték típusát képviseli |
| str | const [String](../../string/)\& | Az enumerációs állandó neve |
| ignoreCase | **bool** | Megadja, hogy az esetet figyelmen kívül kell-e hagyni az enumerációs állandó nevének értelmezésekor |

### Visszatérési érték

Egy objektum, amely a **str**-ban megadott névvel rendelkező enumerációs állandó értékét képviseli.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Object](../../object/)
* Osztály [TypeInfo](../../typeinfo/)
* Osztály [String](../../string/)
* Osztály [EnumValuesBase](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)