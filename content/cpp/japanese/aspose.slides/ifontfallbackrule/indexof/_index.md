---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内の指定されたルールのインデックスを返します。
type: docs
weight: 118
url: /ja/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) メソッド


コレクション内の指定されたルールのインデックスを返します。

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 検索対象のフォント名。 |

### Return Value

フォントがリストに見つからない場合は -1、フォントのインデックスを返します。

## Remarks



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma のインデックスを取得
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## See Also

* クラス [String](../../../system/string/)
* クラス [IFontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)