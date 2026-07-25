---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す GUID を文字列表現に変換します。
type: docs
weight: 79
url: /ja/system/guid/tostring/
---
## Guid::ToString() const メソッド

現在のオブジェクトが表す GUID を文字列表現に変換します。

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const メソッド

指定された文字列形式を使用して、現在のオブジェクトが表す GUID を文字列表現に変換します。

```cpp
String System::Guid::ToString(const String &format) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 使用する形式 |

### 戻り値

現在のオブジェクトが表す GUID の文字列表現

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド

指定された文字列形式とカルチャーを使用して、現在のオブジェクトが表す GUID を文字列表現に変換します。

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 使用する形式 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 使用するカルチャー |

### 戻り値

現在のオブジェクトが表す GUID の文字列表現

## 関連項目

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Guid](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)