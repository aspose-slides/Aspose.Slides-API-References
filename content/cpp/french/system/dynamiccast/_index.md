---
title: DynamicCast()
second_title: Référence API Aspose.Slides pour C++
description: Effectue un cast dynamique sur les objets Exception.
type: docs
weight: 2497
url: /fr/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) fonction


Effectue un cast dynamique sur les objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'Exception cible. |
| TFrom | Type d'Exception source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) fonction


Effectue un cast dynamique sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type de l'objet pointé cible. |
| TFrom | Type de l'objet pointé source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(SmartPtr\<TFrom\>) fonction


Déballe l'énumération encapsulée via cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'énumération cible. |
| TFrom | Type de l'objet pointé source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointeur vers l'objet dont les données doivent être déballees. |

### Valeur de retour

Valeur d'énumération déballe.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(std::nullptr_t) fonction


Effectue un cast dynamique d'objets nuls.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type de l'objet pointé cible. |

### Valeur de retour

nullptr.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(TFrom\&) fonction


Effectue un cast dynamique sur des objets non pointeur.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type cible. |
| TFrom | Type source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Objet source. |

### Valeur de retour

Résultat du cast.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(SmartPtr\<TFrom\>) fonction


Effectue un cast dynamique sur les Objects vers des objets Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type d'Exception cible. |
| TFrom | Type [Object](../object/). |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## System::DynamicCast(TFrom) fonction


Effectue un cast dynamique de IntPtr vers un pointeur.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type cible. |
| TFrom | Type source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | TFrom | Valeur IntPtr source. |

### Valeur de retour

Résultat du cast.

Obsolète
:   Conservé pour la compatibilité descendante. Utilisez ExplicitCast à la place.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Structure [CastResult](../castresult/)
* Structure [IsSmartPtr](../issmartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)