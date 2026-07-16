---
title: setter_post_decrement_wrap()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le traducteur traduit les expressions post-décrément de C# ciblant la propriété d’une classe qui possède un setter et un getter définis, en appel de cette fonction.
type: docs
weight: 2835
url: /fr/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) fonction

Le traducteur traduit les expressions post-décrément de C# ciblant la propriété d’une classe qui possède un setter et un getter définis, en appel de cette fonction.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of the property |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Function pointer pointing to the property's getter free function |
| pSetter | void(*)(T) | Function pointer pointing to the property's setter free function |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fonction

Le traducteur traduit les expressions post-décrément de C# ciblant la propriété d’une instance qui possède un setter et un getter définis, en appel de cette fonction (surcharge pour getter non const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostGet::*)() | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fonction

Le traducteur traduit les expressions post-décrément de C# ciblant la propriété d’une instance qui possède un setter et un getter définis, en appel de cette fonction (surcharge pour getter const).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | The type of the property. |
| Host | - class of instance to be modified |
| HostConstGet | - Host itself, or it's base type, where property's getter is defined |
| HostSet | - Host itself, or it's base type, where property's setter is defined |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| host | Host *const | Instance to call getters and setters for. |
| pGetter | T(HostConstGet::*)() const | Function pointer pointing to the property's getter function |
| pSetter | void(HostSet::*)(T) | Function pointer pointing to the property's setter function |

### Valeur de retour

La valeur de la propriété avant l'incrémentation

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)