---
title: ToUpper()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列のすべての文字を大文字に変換します。
type: docs
weight: 534
url: /ja/system/string/toupper/
---
## String::ToUpper() const メソッド

文字列のすべての文字を大文字に変換します。

```cpp
String System::String::ToUpper() const
```

### 戻り値

変換された文字列。

## String::ToUpper(const SharedPtr\<System::Globalization::CultureInfo\>\&) const メソッド

特定のカルチャを使用して、文字列のすべての文字を大文字に変換します。

```cpp
String System::String::ToUpper(const SharedPtr<System::Globalization::CultureInfo> &cultureInfo) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cultureInfo | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 使用するカルチャ。 |

### 戻り値

変換された文字列。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)