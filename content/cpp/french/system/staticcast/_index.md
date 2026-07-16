---
title: StaticCast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue un cast statique sur des objets SmartPtr.
type: docs
weight: 2523
url: /fr/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) fonction

Effectue un cast statique sur [SmartPtr](../smartptr/) objets.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type du pointeur cible. |
| TFrom | Type du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCast(WeakPtr\<TFrom\> const\&) fonction

Effectue un cast statique sur [WeakPtr](../weakptr/) objets.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type du pointeur cible. |
| TFrom | Type du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCast(std::nullptr_t) fonction

Effectue un cast statique d'objets nuls.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type du pointeur cible. |

### Valeur de retour

nullptr.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCast(TFrom) fonction

Spécialisation pour les types arithmétiques.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) fonction

Effectue le cast de [String](../string/) à [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) fonction

Spécialisation pour les types arithmétiques.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) fonction

Effectue un cast statique sur des objets non pointeurs.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type cible. |
| TFrom | Type source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Objet source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCast(const TFrom\&) fonction

Effectue un cast statique sur des objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'Exception cible. |
| TFrom | Type d'Exception source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCast(SmartPtr\<TFrom\>) fonction

Effectue un cast statique d'objets vers des objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'Exception cible. |
| TFrom | [Object](../object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez ExplicitCast à la place.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Classe [WeakPtr](../weakptr/)
* Classe [String](../string/)
* Classe [Object](../object/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Structure [CastResult](../castresult/)
* Structure [IsSmartPtr](../issmartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)