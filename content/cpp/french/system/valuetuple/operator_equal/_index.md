---
title: operator=()
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 92
url: /fr/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) méthode

```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) méthode

Déconstruit l’objet en ce tuple de valeurs.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Un objet à déconstruire |

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [ValueTuple](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)