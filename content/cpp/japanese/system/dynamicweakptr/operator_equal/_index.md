---
title: operator=()
second_title: Aspose.Slides for C++ API リファレンス
description: スマートポインタをムーブ代入します。
type: docs
weight: 27
url: /ja/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) メソッド


スマートポインタをムーブ代入します。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | ムーブ代入元のポインタ。 |

### 戻り値

自身への参照。

## DynamicWeakPtr::operator=(const SmartPtr_&) メソッド


スマートポインタをコピー代入します。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | コピー代入元のポインタ。 |

### 戻り値

自身への参照。

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) メソッド


スマートポインタをコピー代入します。

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Q | 元のポインテッド型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | コピー代入元のポインタ。 |

### 戻り値

自身への参照。

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) メソッド


スマートポインタを代入します。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | ポインタの値。 |

### 戻り値

自身への参照。

## DynamicWeakPtr::operator=(std::nullptr_t) メソッド


スマートポインタを null に設定します。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### 戻り値

自身への参照。

## 参照

* 型定義 [DynamicWeakPtr_](../dynamicweakptr_/)
* 型定義 [SmartPtr_](../smartptr_/)
* 型定義 [Pointee_](../../smartptr/pointee_/)
* クラス [DynamicWeakPtr](../)
* クラス [SmartPtr](../../smartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)