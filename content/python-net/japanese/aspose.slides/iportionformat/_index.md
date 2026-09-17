---
title: IPortionFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iportionformat/
---
## IPortionFormat クラス

このクラスはテキスト部分の書式設定プロパティを含みます。[`IPortionFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iportionformateffectivedata) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

IPortionFormat 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`bookmark_id`](/slides/python-net/ja/aspose.slides/iportionformat/bookmark_id/) | ブックマーク識別子を取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`smart_tag_clean`](/slides/python-net/ja/aspose.slides/iportionformat/smart_tag_clean/) | スマートタグをクリーンアップするかどうかを決定します。継承は適用されません。<br/>            読み取り/書き込み **bool**. |
| [`line_format`](/slides/python-net/ja/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/ja/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/ja/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/ja/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/ja/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/ja/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/ja/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/ja/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/ja/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/ja/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/ja/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/ja/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/ja/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/ja/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/ja/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/ja/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/ja/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/ja/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/ja/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/ja/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/ja/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/ja/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/ja/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/ja/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/ja/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/ja/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/ja/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/ja/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/ja/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/ja/aspose.slides/iportionformat/hyperlink_manager/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/iportionformat/get_effective/#) | 継承が適用された効果的な部分書式設定データを取得します。 |

### 備考

このクラスは、特定の部分に対して定義されたテキスト部分書式設定プロパティを取得および操作するために使用されます。つまり、値を取得する際には継承が適用されず、ほとんどの場合「undefined」の意味の値が返されます。

継承を含む効果的な書式設定パラメータ値を取得するには、[`IPortionFormat.get_effective`](/slides/python-net/ja/aspose.slides/iportionformat/get_effective) メソッドを使用する必要があります。このメソッドは [`IPortionFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iportionformateffectivedata) インスタンスを返します。

### 参照
* クラス [`IPortionFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iportionformateffectivedata)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)