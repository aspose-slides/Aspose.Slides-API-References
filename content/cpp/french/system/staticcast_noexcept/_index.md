---
title: StaticCast_noexcept()
second_title: Référence de l'API Aspose.Slides for C++
description: Effectue un cast statique sur les objets SmartPtr.
type: docs
weight: 2510
url: /fr/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) function

Effectue un cast statique sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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

Résultat du cast si le cast est autorisé ou nullptr sinon.

Obsolète
:   Conserve pour la compatibilité ascendante. Utilisez AsCast à la place.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) function

Effectue un cast statique sur les objets [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
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

Résultat du cast si le cast est autorisé ou nullptr sinon.

Obsolète
:   Conserve pour la compatibilité ascendante. Utilisez AsCast à la place.

## System::StaticCast_noexcept(const TFrom\&) function

Effectue un cast statique sur les objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type Exception cible. |
| TFrom | Type Exception source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé ou nullptr sinon.

Obsolète
:   Conserve pour la compatibilité ascendante. Utilisez AsCast à la place.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) function

Effectue un cast statique sur les objets Objects vers des objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type Exception cible. |
| TFrom | [Object](../object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé ou nullptr sinon.

Obsolète
:   Conserve pour la compatibilité ascendante. Utilisez AsCast à la place.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Classe [WeakPtr](../weakptr/)
* Classe [Object](../object/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Structure [CastResult](../castresult/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)