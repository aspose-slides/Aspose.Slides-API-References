---
title: WeakPtr()
second_title: Aspose.Slides for C++ API リファレンス
description: null ポインタを作成します。
type: docs
weight: 1
url: /ja/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) コンストラクタ

null ポインタを作成します。

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) コンストラクタ

指定されたオブジェクトへの弱ポインタを作成します。

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) に対して弱ポインタを作成する。 |

## WeakPtr::WeakPtr(const SmartPtr_\&) コンストラクタ

ptr が指す同じポインタを参照する弱ポインタを作成します。

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | ポインタ先の値をコピーする元のポインタ。 |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) コンストラクタ

x が指す同じポインタを参照する弱ポインタを作成します。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | ソースポインタの Pointee 型。 |

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | ポインタ先の値をコピーする元のポインタ。 |

## WeakPtr::WeakPtr(const WeakPtr_\&) コンストラクタ

弱ポインタをコピー構築します。

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | ポインタ先の値をコピーする元のポインタ。 |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) コンストラクタ

弱ポインタをコピー構築します。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | ソースの Pointee 型。 |

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | ポインタ先の値をコピーする元のポインタ。 |

## WeakPtr::WeakPtr(SmartPtr_\&&) コンストラクタ

弱ポインタをムーブ構築します。

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### 引数

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | ムーブ元のポインタ値を取得するポインタ。 |

## 参照

* 型定義 [Pointee_](../../smartptr/pointee_/)
* 型定義 [SmartPtr_](../../smartptr/smartptr_/)
* 型定義 [WeakPtr_](../weakptr_/)
* クラス [WeakPtr](../)
* クラス [SmartPtr](../../smartptr/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)