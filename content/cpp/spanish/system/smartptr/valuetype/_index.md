---
title: ValueType
second_title: Referencia de API de Aspose.Slides para C++
description: "Tipo de almacenamiento del array apuntado. Solo tiene sentido si T es una especialización de System::Array."
type: docs
weight: 508
url: /es/system/smartptr/valuetype/
---
## ValueType typedef

Tipo de almacenamiento del array apuntado. Solo tiene sentido si T es una especialización de [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Ver también

* Clase [SmartPtr](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)