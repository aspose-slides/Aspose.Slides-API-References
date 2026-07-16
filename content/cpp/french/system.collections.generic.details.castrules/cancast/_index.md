---
title: CanCast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie la possibilité de conversion.
type: docs
weight: 40
url: /fr/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

True lorsque une valeur non nullptr est renvoyée après la conversion, sinon false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

True lorsque une valeur non nullptr est renvoyée après la conversion, sinon false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

True lorsque une valeur non nullptr est renvoyée après la conversion, sinon false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Toujours renvoie true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

True lorsque une valeur non nullptr est renvoyée après la conversion, sinon false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Toujours renvoie true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

True si l'opération de conversion a réussi, sinon false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) fonction


Vérifie la possibilité de conversion.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Valeur de retour

Toujours renvoie false.

## Voir aussi

* Structure [CastType](../casttype/)
* Espace de noms [System::Collections::Generic::Details::CastRules](../)
* Bibliothèque [Aspose.Slides](../../)