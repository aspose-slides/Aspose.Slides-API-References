---
title: PrintToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 適切なシリアライザ関数を選択してオブジェクトを文字列に変換します。
type: docs
weight: 1
url: /ja/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) function

適切なシリアライザ関数を選択してオブジェクトを文字列に変換します。

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を印刷するための。 |

### 戻り値

渡されたオブジェクトの[String](../../system/string/) 表現。

## System::TestPredicates::Details::PrintToString(const T\&) function

ICollection スタイルのコンテナを要素（最大 32 個）を文字列に変換して出力します。

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) を印刷するための。 |

### 戻り値

含まれる要素の結合された文字列表現。

## System::TestPredicates::Details::PrintToString(std::nullptr_t) function

nullptr を文字列に変換します。

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### 戻り値

「nullptr」文字列。

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) function

[IEnumerable<bool>](../../system.collections.generic/ienumerable/) コレクションを要素（最大 32 個）を文字列に変換して出力します。

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) を印刷するための。 |

### 戻り値

含まれる要素の結合された文字列表現。

## 参照

* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* 構造体 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 名前空間 [System::TestPredicates::Details](../)
* ライブラリ [Aspose.Slides](../../)