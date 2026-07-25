---
title: Get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたタプルの N 番目の要素を取得する関数です。ベースオブジェクト用のオーバーロードです。
type: docs
weight: 2406
url: /ja/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) 関数


指定されたタプルの N 番目の要素を取得する関数です。ベースオブジェクト用のオーバーロードです。

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| N | 要素のインデックス。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 検査対象のオブジェクト。 |

### 戻り値

N 番目のタプル要素をオブジェクトにキャストした値です。

## System::Get(const T\&) 関数


指定されたタプルの N 番目の要素を取得する関数です。Deconstruct メソッドを持つオブジェクト用のオーバーロードです。

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| N | 要素のインデックス。 |
| T | 検査対象オブジェクトの型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| object | const T\& | 検査対象のオブジェクト。 |

### 戻り値

N 番目のタプル要素の値です。

## System::Get(const SharedPtr\<T\>\&) 関数


指定されたタプルの N 番目の要素を取得する関数です。共有ポインタ用のオーバーロードです。

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| N | 要素のインデックス。 |
| T | 検査対象オブジェクトの型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | 検査対象のオブジェクト。 |

### 戻り値

N 番目のタプル要素の値です。

## System::Get(T\&, const Index\&) 関数


collection[index] 式の実装です。

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | コレクション型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| collection | T\& | コレクションオブジェクト。 |
| index | const [Index](../index/)\& | 型 [System.Index](../index/) の要素インデックス。 |

### 戻り値

計算されたオフセット位置のコレクション要素です。

## System::Get(T\&, const Range\&) 関数


指定されたコレクションの、指定された範囲で定義されたスライスを返します。

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| collection | T\& | スライス対象のコレクション。 |
| range | const [Range](../range/)\& | スライスの境界を示す範囲。 |

### 戻り値

計算された開始オフセットと長さから得られるコレクションのビューまたはスライスです。

## System::Get(const ValueTuple\<Args...\>\&) 関数


値タプルの N 番目の要素を取得します。

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| N | 要素のインデックス。 |
| Args | タプルの要素。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | 要素を取得するタプル。 |

### 戻り値

N 番目のタプル要素の値です。

## 参照

* 型定義 [SharedPtr](../sharedptr/)
* クラス [Object](../object/)
* クラス [Index](../index/)
* クラス [Range](../range/)
* クラス [ValueTuple](../valuetuple/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)