---
title: setter_post_increment_wrap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le traducteur traduit les expressions de post-incrémentation de C# ciblant la propriété d'une classe qui possède un setter et un getter définis, en appel de cette fonction.
type: docs
weight: 2809
url: /fr/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) fonction

Le traducteur traduit les expressions de post-incrémentation de C# ciblant la propriété d’une classe qui possède un setter et un getter définis, en appel de cette fonction.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la propriété |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Pointeur de fonction pointant vers la fonction libre du getter de la propriété |
| pSetter | void(*)(T) | Pointeur de fonction pointant vers la fonction libre du setter de la propriété |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fonction

Le traducteur traduit les expressions de post-incrémentation de C# ciblant la propriété d’une instance qui possède un setter et un getter définis, en appel de cette fonction (surcharge pour getter non const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la propriété. |
| Host | - classe de l'instance à modifier |
| HostGet | - Host lui-même, ou son type de base, où le getter de la propriété est défini |
| HostSet | - Host lui-même, ou son type de base, où le setter de la propriété est défini |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance pour appeler les getters et les setters. |
| pGetter | T(HostGet::*)() | Pointeur de fonction pointant vers la fonction du getter de la propriété |
| pSetter | void(HostSet::*)(T) | Pointeur de fonction pointant vers la fonction du setter de la propriété |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fonction

Le traducteur traduit les expressions de post-incrémentation de C# ciblant la propriété d’une instance qui possède un setter et un getter définis, en appel de cette fonction (surcharge pour getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la propriété. |
| Host | - classe de l'instance à modifier |
| HostConstGet | - Host lui-même, ou son type de base, où le getter de la propriété est défini |
| HostSet | - Host lui-même, ou son type de base, où le setter de la propriété est défini |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance pour appeler les getters et les setters. |
| pGetter | T(HostConstGet::*)() const | Pointeur de fonction pointant vers la fonction du getter de la propriété |
| pSetter | void(HostSet::*)(T) | Pointeur de fonction pointant vers la fonction du setter de la propriété |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)