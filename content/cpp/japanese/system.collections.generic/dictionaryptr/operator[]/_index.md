---
title: operator[]()
second_title: Aspose.Slides for C++ API リファレンス
description: キー型変換で使用するアクセス演算子です。
type: docs
weight: 14
url: /ja/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const method

キー型変換で使用するアクセス演算子です。

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| X | ソースキー型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) キー。 |

### 戻り値

渡されたキーに対応する値への参照を返します（既存の場合も新規作成の場合も同様）。

## DictionaryPtr::operator[](const T\&) const method

アクセス演算子です。

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) キー。 |

### 戻り値

渡されたキーに対応する値への参照を返します（既存の場合も新規作成の場合も同様）。

## 関連項目

* クラス [DictionaryPtr](../)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)