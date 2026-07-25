---
title: BaseDictionary()
second_title: Aspose.Slides for C++ API リファレンス
description: 空のデータ構造を作成します。
type: docs
weight: 14
url: /ja/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() コンストラクタ

空のデータ構造を作成します。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) コンストラクタ

基になるマップコンストラクタに転送するためのコンストラクタです。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Args | マップに転送する引数の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | int | 基になるマップに転送する引数。 |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) コンストラクタ

コピーコンストラクタ。

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Args | マップコンストラクタ引数の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) からデータをコピーする。 |
| args | const Args\&... | 基になるマップコンストラクタに転送する引数。 |

## BaseDictionary::BaseDictionary(BaseType *) コンストラクタ

コピーコンストラクタ。

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) からデータをコピーする。 |

## 参照

* Typedef [BaseType](../basetype/)
* クラス [BaseDictionary](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)