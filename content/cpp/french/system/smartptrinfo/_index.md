---
title: SmartPtrInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe de service pour tester et modifier le contenu de SmartPtr sans connaître le type final. Utilisée pour la collecte des déchets et la détection des références cycliques, etc. Considérez-la comme un 'pointeur vers pointeur'. Nous ne pouvons pas utiliser le type de base de SmartPtr car il n'en possède pas ; à la place, nous utilisons cette classe 'info'.
type: docs
weight: 1223
url: /fr/system/smartptrinfo/
---
## SmartPtrInfo classe

Classe de service pour tester et modifier le contenu de [SmartPtr](../smartptr/) sans connaître le type final. Utilisée pour la collecte des déchets et la détection des références cycliques, etc. Considérez-le comme un 'pointeur vers pointeur'. Nous ne pouvons pas utiliser le type de base de [SmartPtr](../smartptr/) car il n'en a pas ; à la place, nous utilisons cette classe 'info'.

```cpp
class SmartPtrInfo
```

## Méthodes

| Méthode | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Obtient le pointeur brut vers l'objet référencé. |
| [Object](../object/) * [getObject](./getobject/)() const | Obtient l'objet vers lequel le pointeur référencé pointe. |
| [Object](../object/) * [getOwned](./getowned/)() const | Obtient le pointeur appartenant à l'objet. |
|  [operator bool](./operator_bool/)() const | Vérifie si l'objet info pointe vers un pointeur non nul. |
| **bool** [operator!](./operator_not/)() const | Vérifie si l'objet info ne pointe pas vers un pointeur non nul. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Permet d'appeler les méthodes de [Object](../object/) pointées par le pointeur référencé. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Compare les valeurs des pointeurs référencés par deux objets info. |
|  [SmartPtrInfo](./smartptrinfo/)() | Crée un objet [SmartPtrInfo](./) vide. |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Crée un objet [SmartPtrInfo](./) avec les informations sur un pointeur intelligent spécifique. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)