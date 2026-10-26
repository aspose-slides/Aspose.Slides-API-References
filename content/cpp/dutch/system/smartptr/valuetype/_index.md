---
title: ValueType
second_title: Aspose.Slides voor C++ API Referentie
description: "Opslagtype van een aangewezen array. Alleen zinvol als T een specialisatie is van System::Array."
type: docs
weight: 508
url: /nl/system/smartptr/valuetype/
---
## ValueType typedef


Opslagtype van een aangewezen array. Alleen zinvol als T een specialisatie van [System::Array](../../array/) is.

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Zie ook

* Klasse [SmartPtr](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)