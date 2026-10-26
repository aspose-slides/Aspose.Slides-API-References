---
title: UnboxToNullable()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Rozbalí objekt do nullable typu.
type: docs
weight: 79
url: /cs/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metoda

Rozbalí objekt do nullable typu.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k rozbalení. |
| safe | **bool** | Pokud je true, vrátí nullptr při selhání, jinak vyvolá InvalidCastException. |

### Návratová hodnota

Rozbalená nullable hodnota (může být null).

## Viz také

* Třída [Nullable](../../nullable/)
* Třída [SmartPtr](../../smartptr/)
* Třída [Object](../../object/)
* Třída [ObjectExt](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)