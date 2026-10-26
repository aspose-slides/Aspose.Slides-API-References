---
title: DynamicWeakPtr()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un pointeur intelligent nul.
type: docs
weight: 1
url: /fr/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructeur

Crée un pointeur intelligent nul.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructeur

Crée un pointeur intelligent pointant vers l'objet fourni.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointeur. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructeur

Construit une copie du pointeur intelligent.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointeur intelligent dont on copie les informations du pointeur. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructeur

Construit une copie du pointeur intelligent.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type du pointeur source. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointeur intelligent dont on copie les informations du pointeur. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructeur

Construit une copie du pointeur intelligent.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Pointeur intelligent dont on copie les informations du pointeur. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructeur

Construit le pointeur intelligent par déplacement.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointeur intelligent dont on déplace les informations du pointeur. Devient inutilisable après l'appel. |

## Voir aussi

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Classe [DynamicWeakPtr](../)
* Classe [SmartPtr](../../smartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)