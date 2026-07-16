---
title: ExplicitCast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit le type source en type résultat à l'aide d'un cast explicite. Utilisé lorsque les types source et résultat sont identiques.
type: docs
weight: 2588
url: /fr/system/explicitcast/
---
## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé lorsque les types Source et Result sont identiques.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé lorsqu'un cast simple de type constructeur est nécessaire.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour les enveloppes d'exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour convertir un objet en exception.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé lorsque le source et le résultat sont tous deux des pointeurs intelligents (sans SmartPtr<...> explicite dans le type résultat).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(Source) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé lors du cast d'un pointeur brut vers un pointeur intelligent.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | Source | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé lorsque le source et le résultat sont tous deux des pointeurs intelligents (avec SmartPtr<...> explicite dans le type résultat).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le déballage d'un objet vers nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour emballer nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le déballage d'un objet nullable.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour l'emballage d'énumération.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour copier des types valeur sur le tas lorsque le type valeur doit être référencé comme pointeur intelligent (dans les génériques contraints par un type d'interface mais spécialisés avec une structure implémentant cette interface).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour obtenir des interfaces à partir de types valeur.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour l'emballage commun.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour l'emballage [System::String](../string/).

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le déballage d'interfaces.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le déballage commun.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le cast de nullptr.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## System::ExplicitCast(const Source\&) fonction

Convertit le type Source en type Result à l'aide d'un cast explicite. Utilisé pour le cast entre tableaux.

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Source | Le type source. |
| Result | Le type résultat. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) à caster. |

### Valeur de retour

Le résultat du cast.

## Voir aussi

* Typedef [Exception](../exception/)
* Classe [SmartPtr](../smartptr/)
* Classe [BoxedValueBase](../boxedvaluebase/)
* Structure [CastResult](../castresult/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)