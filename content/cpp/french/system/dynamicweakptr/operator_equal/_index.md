---
title: operator=()
second_title: Référence API Aspose.Slides for C++
description: Attribue par déplacement le pointeur intelligent.
type: docs
weight: 27
url: /fr/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) method


Attribue par déplacement le pointeur intelligent.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointeur depuis lequel assigner par déplacement. |

### Valeur de retour

Référence à soi-même.

## DynamicWeakPtr::operator=(const SmartPtr_\&) method


Attribue par copie le pointeur intelligent.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointeur depuis lequel assigner par copie. |

### Valeur de retour

Référence à soi-même.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) method


Attribue par copie le pointeur intelligent.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type de l’objet pointé source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointeur depuis lequel assigner par copie. |

### Valeur de retour

Référence à soi-même.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) method


Attribue le pointeur intelligent.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Valeur du pointeur. |

### Valeur de retour

Référence à soi-même.

## DynamicWeakPtr::operator=(std::nullptr_t) method


Met le pointeur intelligent à nul.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Valeur de retour

Référence à soi-même.

## Voir aussi

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Classe [DynamicWeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)