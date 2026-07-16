---
title: DynamicCast_noexcept()
second_title: Référence de l'API Aspose.Slides pour C++
description: Anciennes conversions obsolètes. Seront supprimées dans les versions futures.
type: docs
weight: 2484
url: /fr/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) fonction


Anciennes conversions obsolètes. Seront supprimées dans les versions futures.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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

Résultat du cast si le cast est autorisé ou nullptr sinon.
## Remarques


Effectue un cast dynamique sur les objets Exception. Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez AsCast à la place.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) fonction


Effectue un cast dynamique sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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
:   Conservé pour la compatibilité ascendante. Utilisez AsCast à la place.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) fonction


Effectue un cast dynamique sur des objets vers des objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'Exception cible. |
| TFrom | Type [Object](../object/) source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé ou nullptr sinon.

Obsolète
:   Conservé pour la compatibilité ascendante. Utilisez AsCast à la place.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)