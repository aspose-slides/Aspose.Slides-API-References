---
title: IsNull()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定の値が null かどうかを確認します。算術型および列挙型向けのバージョンです。
type: docs
weight: 1
url: /ja/system/testtools/isnull/
---
## TestTools::IsNull(T) メソッド

特定の値が null かどうかを確認します。[Version](../../version/) は算術型および列挙型に対して使用します。

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | T | null かどうかを確認する値。 |

### 戻り値

常に false を返します。

## TestTools::IsNull(const T\&) メソッド

特定の値が null かどうかを確認します。[Version](../../version/) は非算術型および非列挙型の値に対して使用します。

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const T\& | null かどうかを確認する値。 |

### 戻り値

オブジェクトが nullptr と比較された場合は true、そうでない場合は false を返します。

## TestTools::IsNull(const SharedPtr\<T\>\&) メソッド

特定の値が null かどうかを確認します。[Version](../../version/) は非算術型の値に対して使用します。

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | チェック対象の値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | null かどうかを確認する値。 |

### 戻り値

オブジェクトが nullptr と比較された場合は true、そうでない場合は false を返します。

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) メソッド

特定の値が null かどうかを確認します。[Version](../../version/) はキーと値のペアに対して使用します。

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| K | キーの型。 |
| V | 値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | ペアオブジェクト。 |

### 戻り値

ペアが null と見なされる場合は true、そうでない場合は false を返します。

## TestTools::IsNull(const System::String\&) メソッド

文字列が null かどうかを確認します。

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) を確認する。 |

### 戻り値

文字列が null と見なされる場合は true、そうでない場合は false を返します。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* クラス [String](../../string/)
* 構造体 [TestTools](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)