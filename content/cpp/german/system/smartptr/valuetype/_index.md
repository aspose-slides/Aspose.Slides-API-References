---
title: ValueType
second_title: Aspose.Slides für C++ API-Referenz
description: "Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von System::Array ist."
type: docs
weight: 508
url: /de/system/smartptr/valuetype/
---
## ValueType typedef


Speichertyp des referenzierten Arrays. Nur sinnvoll, wenn T eine Spezialisierung von [System::Array](../../array/) ist.

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Siehe auch

* Klasse [SmartPtr](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)