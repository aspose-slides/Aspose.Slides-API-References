---
title: UnboxToNullable()
second_title: Aspose.Slides för C++ API-referens
description: Avpaketerar objekt till en nullable-typ.
type: docs
weight: 79
url: /sv/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metod

Avpaketerar objekt till en nullable-typ.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Måldatatyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) för att avpaketera. |
| safe | **bool** | Om true, returnera nullptr vid fel, annars kasta InvalidCastException. |

### Returvärde

Avpaketerat nullable-värde (kan vara null).

## Se också

* Klass [Nullable](../../nullable/)
* Klass [SmartPtr](../../smartptr/)
* Klass [Object](../../object/)
* Klass [ObjectExt](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)