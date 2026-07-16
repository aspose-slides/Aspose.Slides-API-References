---
title: AssemblyTypeRegistration
second_title: Référence de l'API Aspose.Slides pour C++
description: Singleton permettant d'enregistrer le type dans l'assembly en cours d'exécution.
type: docs
weight: 27
url: /fr/system.reflection/assemblytyperegistration/
---
## AssemblyTypeRegistration classe

Singleton pour enregistrer le type dans l'assembly en cours d'exécution.

```cpp
template<typename T>class AssemblyTypeRegistration : public System::Reflection::AssemblyTypeRegistrationBase
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à enregistrer. |
## Méthodes

| Méthode | Description |
| --- | --- |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)() | Crée le singleton, enregistrant ainsi le type dans l'assembly en cours d'exécution. |
|  [AssemblyTypeRegistration](./assemblytyperegistration/)(const [SharedPtr](../../system/sharedptr/)\<[Assembly](../assembly/)\>\&) | Crée le singleton, enregistrant ainsi le type dans l'assembly spécifié. |

## Voir aussi

* Classe [AssemblyTypeRegistrationBase](../assemblytyperegistrationbase/)
* Espace de noms [System::Reflection](../)
* Bibliothèque [Aspose.Slides](../../)