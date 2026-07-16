---
title: Ref()
second_title: Référence API Aspose.Slides pour C++
description: Crée une référence à l'objet DynamicWeakPtr. Utilisé par le traducteur lors du passage des arguments de fonction par référence.
type: docs
weight: 2419
url: /fr/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) fonction


Crée une référence à l'objet [DynamicWeakPtr](../dynamicweakptr/). Utilisé par le traducteur lors du passage d'arguments de fonction par référence.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type du pointeur. |
| trunkMode | Mode du pointeur intelligent lui-même. |
| weakLeafs | Index des arguments de modèle pour lesquels la méthode SetTemplateWeakPtr doit être appelée. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Pointeur intelligent sur lequel créer la référence. |

### Valeur de retour

Référence de pointeur intelligent.

## System::Ref(T\&) fonction


Fonction d’aide pour acquérir des références aux objets. Utilisée pour garantir que [System::DynamicWeakPtr](../dynamicweakptr/) met à jour l’objet référencé après les affectations.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type sur lequel créer la référence. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T\& | Valeur sur laquelle créer la référence. |

### Valeur de retour

Référence à la valeur transmise à cette fonction.

## Voir aussi

* Classe [DynamicWeakPtr](../dynamicweakptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)