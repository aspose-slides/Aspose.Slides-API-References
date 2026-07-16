---
title: AsCast()
second_title: Référence API Aspose.Slides pour C++
description: Convertit le type source en le type résultat en utilisant le cast de l'opérateur 'as'. Utilisé lorsque un cast simple de type constructeur est nécessaire.
type: docs
weight: 2601
url: /fr/system/ascast/
---
## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé lorsque un cast simple de type constructeur est nécessaire.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé lorsque le type source et le type résultat sont identiques.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour les enveloppes d'exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie nullptr si aucune conversion n'est disponible.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour convertir un objet en exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie nullptr si aucune conversion n'est disponible.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé lorsque le source et le résultat sont tous deux des pointeurs intelligents.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie nullptr si aucune conversion n'est disponible.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé lorsque le source et le résultat sont tous deux des pointeurs intelligents (avec SmartPtr<...> explicite dans le type résultat).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie nullptr si aucune conversion n'est disponible.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour désencapsuler (unboxing) un objet vers un nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie un nullable vide si aucune conversion n'est disponible.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Déballage (unboxing) invalide vers un type non-objet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Renvoie toujours null.

## System::AsCast(const Source\&) fonction


Déballage (unboxing) invalide vers un type non-objet.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Renvoie toujours null.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour encapsuler (boxing) un objet nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour encapsuler (boxing) un objet commun.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour encapsuler (boxing) un objet commun.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour désencapsuler (unboxing) une chaîne de caractères.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour le cas nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast.

## System::AsCast(const Source\&) fonction


Convertit le type source en le type résultat en utilisant le cast d'opérateur 'as'. Utilisé pour convertir entre tableaux.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à convertir. |

### Valeur de retour

Le résultat du cast. Renvoie nullptr si aucune conversion n'est disponible pour un membre du tableau.

## Voir aussi

* Typedef [Exception](../exception/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)