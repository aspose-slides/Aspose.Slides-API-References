---
title: setter_wrap()
second_title: Référence API Aspose.Slides pour C++
description: Surcharge pour les fonctions setter statiques avec conversion de type.
type: docs
weight: 2783
url: /fr/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) fonction


Surcharge pour les fonctions setter statiques avec conversion de type.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur. |
| T2 | Type attendu par la fonction setter. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pSetter | void(*)(T2) | Référence de fonction setter statique. |
| value | T | Valeur à définir. |

### Valeur de retour

valeur définie.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) fonction


Surcharge pour les fonctions setter d'instance avec conversion de type.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur. |
| T2 | Type attendu par la fonction setter. |
| Host | Type d'instance. |
| HostSet | - L'hôte lui-même, ou son type de base, où le setter de la propriété est défini. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | [Object](../object/) pour appeler la fonction setter. |
| pSetter | void(HostSet::*)(T2) | Référence de fonction setter. |
| value | T | Valeur à définir. |

### Valeur de retour

valeur définie.

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)