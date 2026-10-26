---
title: operator=()
second_title: Référence de l'API Aspose.Slides for C++
description: Effectue une affectation par déplacement de l'objet SmartPtr. x devient inutilisable.
type: docs
weight: 27
url: /fr/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) méthode

Effectue une affectation par déplacement de l'objet [SmartPtr](../). x devient inutilisable.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pointeur pour l'affectation par déplacement. |

### Valeur de retour

Référence à cet objet.

## SmartPtr::operator=(const SmartPtr_&) méthode

Effectue une affectation par copie de l'objet [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Pointeur pour l'affectation par copie. |

### Valeur de retour

Référence à cet objet.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) méthode

Effectue une affectation par copie de l'objet [SmartPtr](../). Effectue les conversions de type nécessaires.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type de l'objet pointé par x. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | Pointeur pour l'affectation par copie. |

### Valeur de retour

Référence à cet objet.

## SmartPtr::operator=(Pointee_ *) méthode

Assigne le pointeur brut à l'objet [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Valeur du pointeur à assigner. |

### Valeur de retour

Référence à cet objet.

## SmartPtr::operator=(std::nullptr_t) méthode

Définit la valeur du pointeur sur nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Valeur de retour

Référence à cet objet.

## Voir aussi

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)