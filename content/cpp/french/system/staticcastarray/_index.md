---
title: StaticCastArray()
second_title: Référence API Aspose.Slides pour C++
description: Effectue le transtypage des éléments du tableau spécifié vers un type différent. Remplacement pour les cas où From est un objet SmartPtr.
type: docs
weight: 2939
url: /fr/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) fonction

Effectue le transtypage des éléments du tableau spécifié vers un type différent. Remplacement pour les cas où From est [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| To | Le type vers lequel les éléments du tableau spécifié doivent être convertis |
| From | Le type des éléments du tableau dont les éléments doivent être convertis |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Pointeur partagé vers le tableau contenant les éléments à convertir |

### Valeur de retour

Un pointeur vers un nouveau tableau contenant des éléments de type **To** équivalents aux éléments de **from**

Obsolète
:   Ajouté pour compatibilité ascendante. Utilisez ExplicitCast à la place.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) fonction

Effectue le transtypage des éléments du tableau spécifié vers un type différent. Remplacement pour les cas où From est Boxable et To est [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| To | Le type vers lequel les éléments du tableau spécifié doivent être convertis |
| From | Le type des éléments du tableau dont les éléments doivent être convertis |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Pointeur partagé vers le tableau contenant les éléments à convertir |

### Valeur de retour

Un pointeur vers un nouveau tableau contenant des éléments de type **To** équivalents aux éléments de **from**

Obsolète
:   Ajouté pour compatibilité ascendante. Utilisez ExplicitCast à la place.

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Class [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)