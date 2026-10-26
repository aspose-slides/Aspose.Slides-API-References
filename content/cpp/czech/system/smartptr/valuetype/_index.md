---
title: ValueType
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Typ úložiště ukazovaného pole. Smysluplné pouze pokud je T specializací System::Array."
type: docs
weight: 508
url: /cs/system/smartptr/valuetype/
---
## typedef ValueType


Typ úložiště ukazovaného pole. Smysluplné pouze pokud je T specializací [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Viz také

* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)