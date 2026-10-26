---
title: WeakPtr()
second_title: Aspose.Slides for C++ API 參考
description: 建立空指標。
type: docs
weight: 1
url: /zh-hant/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) 建構子

建立空指標。

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) 建構子

建立指向給定物件的弱指標。

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) 用於建立弱指標。 |

## WeakPtr::WeakPtr(const SmartPtr_\&) 建構子

建立弱指標，參考與 ptr 所指向的相同指標。

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | 用於複製指向值的指標。 |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) 建構子

建立弱指標，參考與 x 所指向的相同指標。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 來源指向類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 用於複製指向值的指標。 |

## WeakPtr::WeakPtr(const WeakPtr_\&) 建構子

複製建構弱指標。

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | 用於複製指向值的指標。 |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) 建構子

複製建構弱指標。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 來源指向類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | 用於複製指向值的指標。 |

## WeakPtr::WeakPtr(SmartPtr_\&&) 建構子

移動建構弱指標。

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | 用於移動指向值的指標。 |

## 另見

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)