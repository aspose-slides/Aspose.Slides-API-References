---
title: setter_increment_wrap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le traducteur traduit les expressions d'incrémentation de C# ciblant la propriété d'une classe qui possède des accesseurs getter et setter définis, en appel de cette fonction.
type: docs
weight: 2796
url: /fr/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) function

Le traducteur traduit les expressions d’incrémentation de C# ciblant la propriété d’une classe qui possède des accesseurs getter et setter définis, en appel de cette fonction.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la propriété |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Pointeur de fonction pointant vers la fonction libre getter de la propriété |
| pSetter | void(*)(T) | Pointeur de fonction pointant vers la fonction libre setter de la propriété |

### Valeur de retour

La valeur incrémentée de la propriété

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

Le traducteur traduit les expressions d’incrémentation de C# ciblant la propriété d’une classe qui possède des accesseurs getter et setter définis, en appel de cette fonction.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la propriété |
| Host | - classe de l'instance à modifier |
| HostGet | - l'hôte lui-même, ou son type de base, où le getter de la propriété est défini |
| HostSet | - l'hôte lui-même, ou son type de base, où le setter de la propriété est défini |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | Un pointeur vers un objet dont la propriété doit être incrémentée |
| pGetter | T(HostGet::*)() | Pointeur de fonction pointant vers la méthode getter de la propriété |
| pSetter | void(HostSet::*)(T) | Pointeur de fonction pointant vers la méthode setter de la propriété |

### Valeur de retour

La valeur incrémentée de la propriété

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)