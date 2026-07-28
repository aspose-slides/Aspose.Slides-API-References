---
title: UnboxToNullable()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Rozpakowuje obiekt do typu nullable.
type: docs
weight: 79
url: /pl/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metoda

Rozpakowuje obiekt do typu nullable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do rozpakowania. |
| safe | **bool** | Jeśli true, zwróć nullptr w przypadku niepowodzenia, w przeciwnym razie rzuć InvalidCastException. |

### Wartość zwracana

Rozpakowana wartość nullable (może być null).

## Zobacz także

* Klasa [Nullable](../../nullable/)
* Klasa [SmartPtr](../../smartptr/)
* Klasa [Object](../../object/)
* Klasa [ObjectExt](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)