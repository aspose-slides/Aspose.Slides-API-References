---
title: FontFamily()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された名前のフォントファミリを表す FontFamily クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) コンストラクタ

指定された名前のフォントファミリを表す [FontFamily](../) クラスの新しいインスタンスを作成します。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | フォント ファミリ名 |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) コンストラクタ

指定された名前で、指定された FontCollection 内に [FontFamily](../) の新しいインスタンスを作成します。

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | フォント ファミリ名 |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | このインスタンスを含む FontCollection |

## FontFamily::FontFamily(Text::GenericFontFamilies) コンストラクタ

指定されたジェネリック フォントファミリから [FontFamily](../) の新しいインスタンスを作成します。

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | [FontFamily](../) を構築するための GenericFontFamilies の値 |

## 参照

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [FontFamily](../)
* クラス [FontCollection](../../../system.drawing.text/fontcollection/)
* 名前空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)