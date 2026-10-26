---
title: Join()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列を区切りとして配列を結合します。
type: docs
weight: 846
url: /ja/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) メソッド

文字列を区切りとして配列を結合します。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) を配列要素間に配置する区切り文字です。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) は結合するパーツの集合です。 |
| startIndex | int | 結合を開始する配列の最初のインデックスです。 |
| count | int | 結合する配列要素の数です。-1 は「配列の末尾まで」を意味します。 |

### 戻り値

[String](../) は結合された配列要素を表します。

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) メソッド

文字列を区切りとして配列を結合します。

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) を配列要素間に配置する区切り文字です。 |
| parts | const System::Details::ArrayView\<[String](../)\>\& | 結合するパーツの ArrayViewです。 |
| startIndex | int | 結合を開始する配列の最初のインデックスです。 |
| count | int | 結合する配列要素の数です。-1 は「配列の末尾まで」を意味します。 |

### 戻り値

[String](../) は結合された配列要素を表します。

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) メソッド

文字列を区切りとして配列を結合します。

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) を配列要素間に配置する区切り文字です。 |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - 部分の列挙可能オブジェクト |

### 戻り値

[String](../) は結合された要素を表します。

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) メソッド

文字列を区切りとして配列を結合します。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) を配列要素間に配置する区切り文字です。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) は結合する部分の集合です。 |

### 戻り値

[String](../) は結合された要素を表します。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [Object](../../object/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)