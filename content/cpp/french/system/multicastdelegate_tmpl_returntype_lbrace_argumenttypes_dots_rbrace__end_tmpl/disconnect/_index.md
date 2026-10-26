---
title: disconnect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime le délégué spécifié de la collection de délégués.
type: docs
weight: 170
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) méthode


Supprime le délégué spécifié de la collection de délégués.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | Le délégué à supprimer de la collection |

### Valeur de retour

Une référence à l'objet

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) méthode


Supprime la méthode non statique spécifiée de l'objet spécifié de la collection de délégués.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | Le type de la méthode non statique qui doit être supprimée de la collection de délégués |
| ClassType | Le type de l'objet dont la méthode doit être supprimée de la collection de délégués |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un pointeur vers la méthode non statique de l'objet spécifié |
| obj | ClassType * | Un pointeur vers un membre de l'objet dont la méthode doit être supprimée de la collection de délégués |

### Valeur de retour

Une référence à l'objet

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) méthode


Supprime la méthode non statique spécifiée de l'objet spécifié de la collection de délégués.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | Le type de la méthode non statique qui doit être supprimée de la collection de délégués |
| ClassType | Le type de l'objet dont la méthode doit être supprimée de la collection de délégués |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un pointeur vers la méthode non statique de l'objet spécifié |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un pointeur partagé vers un membre de l'objet dont la méthode doit être supprimée de la collection de délégués |

### Valeur de retour

Une référence à l'objet

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) méthode


Supprime l'objet MulticastDelegate spécifié de la collection de délégués.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Une instance de la classe MulticastDelegate à supprimer de la collection de délégués |

### Valeur de retour

Une référence à l'objet

## Voir aussi

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Méthode [MulticastDelegate](../multicastdelegate/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)