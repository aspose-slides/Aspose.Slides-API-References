---
title: connect()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute le délégué spécifié à la collection.
type: docs
weight: 144
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) méthode


Ajoute le délégué spécifié à la collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | Le délégué à ajouter à la collection |

### Valeur de retour

Une référence à l'objet lui-même

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) méthode


Ajoute l'objet fonction spécifié à la collection de délégués. L'objet fonction est converti en type de délégué Callback avant d'être ajouté à la collection.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| R | Le type de retour de l'objet fonction à ajouter à la collection |
| Args | La liste des arguments de l'objet fonction à ajouter à la collection |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | L'objet fonction à ajouter à la collection |

### Valeur de retour

Une référence à l'objet lui-même

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) méthode


Ajoute l'objet MulticastDelegate spécifié à la collection de délégués.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | Une instance de la classe MulticastDelegate à ajouter à la collection de délégués |

### Valeur de retour

Une référence à l'objet lui-même

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) méthode


Ajoute la méthode non statique spécifiée de l'objet spécifié à la collection de délégués.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | Le type de la méthode non statique à ajouter à la collection de délégués |
| ClassType | Le type de l'objet dont la méthode doit être ajoutée au délégué |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un pointeur vers la méthode non statique de l'objet spécifié |
| obj | ClassType * | Un pointeur vers une méthode membre d'objet qui doit être ajoutée à la collection de délégués |

### Valeur de retour

Une référence à l'objet lui-même

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) méthode


Ajoute la méthode non statique spécifiée de l'objet spécifié à la collection de délégués.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| MemberType | Le type de la méthode non statique à ajouter à la collection de délégués |
| ClassType | Le type de l'objet dont la méthode doit être ajoutée à la collection de délégués |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | Un pointeur vers la méthode non statique de l'objet spécifié |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | Un pointeur partagé vers une méthode membre d'objet qui doit être ajoutée à la collection de délégués |

### Valeur de retour

Une référence à l'objet lui-même

## Voir aussi

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Méthode [MulticastDelegate](../multicastdelegate/)
* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)