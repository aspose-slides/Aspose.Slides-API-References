---
title: operator=()
second_title: Aspose.Slides för C++ API-referens
description: Flytttilldelar smart pekare.
type: docs
weight: 27
url: /sv/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) metod

Flytttilldelar smart pekare.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pekare att flytttilldela värde från. |

### Returvärde

Självreferens.

## DynamicWeakPtr::operator=(const SmartPtr_&) metod

Kopieringstilldelar smart pekare.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Pekare att kopiera tilldelningsvärde från. |

### Returvärde

Självreferens.

## DynamicWeakPtr::operator=(const SmartPtr<Q>&) metod

Kopieringstilldelar smart pekare.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Q | Källtyp för pekartyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)<Q>& | Pekare att kopiera tilldelningsvärde från. |

### Returvärde

Självreferens.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metod

Tilldelar smart pekare.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Pekarvärde. |

### Returvärde

Självreferens.

## DynamicWeakPtr::operator=(std::nullptr_t) metod

Sätter smart pekare till null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Returvärde

Självreferens.

## Se även

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Klass [DynamicWeakPtr](../)
* Klass [SmartPtr](../../smartptr/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)