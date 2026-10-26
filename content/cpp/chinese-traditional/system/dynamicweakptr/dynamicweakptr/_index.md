---
title: DynamicWeakPtr()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立空的智慧指標。
type: docs
weight: 1
url: /zh-hant/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor


建立空的智慧指標。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor


建立指向給定物件的智慧指標。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | 被指向物件。 |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor


複製建構智慧指標。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 用於複製被指向資訊的智慧指標。 |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor


複製建構智慧指標。

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 來源指標指向的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 用於複製被指向資訊的智慧指標。 |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor


複製建構智慧指標。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | 用於複製被指向資訊的智慧指標。 |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor


移動建構智慧指標。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 用於從中移動被指向資訊的智慧指標。呼叫後將無法使用。 |

## 另見

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)