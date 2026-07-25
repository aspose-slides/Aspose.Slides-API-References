---
title: MakeArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された初期化リストの要素で新しい Array オブジェクトを構築し、要素で埋め、Array オブジェクトを指すスマートポインタを返すファクトリ関数です。
type: docs
weight: 2029
url: /ja/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) 関数


指定された初期化リストの要素で [Array](../array/) オブジェクトを構築し、要素で埋め、[Array](../array/) オブジェクトを指すスマートポインタを返すファクトリ関数です。

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数が構築する [Array](../array/) オブジェクトの要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| init | std::initializer_list\<T\> | 配列を埋める要素を含む初期化リスト |

### 戻り値

構築された [Array](../array/) オブジェクトを指すスマートポインタ

## System::MakeArray(Args\&&...) 関数


指定された引数をコンストラクタに渡して新しい [Array](../array/) オブジェクトを構築するファクトリ関数です。

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数が構築する [Array](../array/) オブジェクトの要素型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | Args\&&... | 構築中の [Array](../array/) オブジェクトのコンストラクタに渡される引数 |

### 戻り値

構築された [Array](../array/) オブジェクトを指すスマートポインタ

## System::MakeArray(Integral, Args\&&...) 関数


指定された引数をコンストラクタに渡して新しい [Array](../array/) オブジェクトを構築するファクトリ関数です。

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 関数が構築する [Array](../array/) オブジェクトの要素型 |
| Integral | 配列サイズの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| size | Integral | 作成される配列のサイズ |
| args | Args\&&... | 構築中の [Array](../array/) オブジェクトのコンストラクタに渡される引数 |

### 戻り値

構築された [Array](../array/) オブジェクトを指すスマートポインタ

## 関連項目

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)