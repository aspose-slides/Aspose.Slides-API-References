---
title: Cast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit le type source en type résultat. Utilisé lorsque les types source et résultat sont identiques.
type: docs
weight: 14
url: /fr/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque les types source et résultat sont identiques.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le type source peut être converti statiquement en type résultat.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque les types ne sont pas identiques et que le type source ne peut pas être converti statiquement en type résultat.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le type source est empaqueté dans l’instance de classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le type source est désémballé depuis l’instance de classe [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le type source est empaqueté dans l’instance de classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le type source est désémballé depuis l’instance de classe [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## System::Collections::Generic::Details::CastRules::Cast(Source) fonction


Convertit le type source en type résultat. Utilisé lorsque le cast est invalide ou que la conversion est explicite.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Le résultat du cast.

## Voir aussi

* Structure [CastType](../casttype/)
* Espace de noms [System::Collections::Generic::Details::CastRules](../)
* Bibliothèque [Aspose.Slides](../../)