---
title: operator=()
second_title: Aspose.Slides для C++: справочник API
description: Перемещающее присваивание умного указателя.
type: docs
weight: 27
url: /ru/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) метод

Перемещающее присваивание умного указателя.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Указатель, из которого перемещается значение. |

### Return Value

Ссылка на себя.

## DynamicWeakPtr::operator=(const SmartPtr_&) метод

Копирующее присваивание умного указателя.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Указатель, из которого копируется значение. |

### Return Value

Ссылка на себя.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>&) метод

Копирующее присваивание умного указателя.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Исходный тип pointee. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)<Q>& | Указатель, из которого копируется значение. |

### Return Value

Ссылка на себя.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) метод

Присваивание умного указателя.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Значение указателя. |

### Return Value

Ссылка на себя.

## DynamicWeakPtr::operator=(std::nullptr_t) метод

Устанавливает умный указатель в null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Return Value

Ссылка на себя.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)