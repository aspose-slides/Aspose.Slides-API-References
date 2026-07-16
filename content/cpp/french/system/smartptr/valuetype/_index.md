---
title: ValueType
second_title: Référence de l'API Aspose.Slides pour C++
description: "Type de stockage du tableau pointé. N'a de sens que si T est une spécialisation de System::Array."
type: docs
weight: 508
url: /fr/system/smartptr/valuetype/
---
## ValueType typedef

Type de stockage du tableau pointé. N'a de sens que si T est une spécialisation de [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)