---
title: GetHashCode()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient le code de hachage sur un type arbitraire. Appelle Object::GetHashCode() pour cela."
type: docs
weight: 1
url: /fr/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) méthode

Obtient le code de hachage sur un type arbitraire. Appelle [Object::GetHashCode()](../../../system/object/gethashcode/) pour cela.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type pour lequel obtenir le code de hachage. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) pour obtenir des informations à partir de. |

### Valeur de retour

Valeur du code de hachage telle que calculée par l'implémentation cible.

## Voir aussi

* Classe [SmartPtr](../../../system/smartptr/)
* Classe [RuntimeHelpers](../)
* Espace de noms [System::Runtime::CompilerServices](../../)
* Bibliothèque [Aspose.Slides](../../../)