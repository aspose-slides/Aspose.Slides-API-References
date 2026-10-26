---
title: BasePortionFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/baseportionformat/
---
## BasePortionFormat クラス

テキストの一部の共通書式設定プロパティ。

**Inheritance:**[`BasePortionFormat`](/slides/python-net/ja/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

BasePortionFormat 型は以下のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/ja/aspose.slides/baseportionformat/line_format/) | テキストのアウトライン用の LineFormat プロパティを返します。継承は適用されません。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/ja/aspose.slides/baseportionformat/fill_format/) | テキストの FillFormat プロパティを返します。継承は適用されません。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ja/aspose.slides/baseportionformat/effect_format/) | テキストの EffectFormat プロパティを返します。継承は適用されません。<br/>            読み取り専用 [`IEffectFormat`](/slides/python-net/ja/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/ja/aspose.slides/baseportionformat/highlight_color/) | テキストのハイライトに使用される色を返します。継承は適用されません。<br/>            読み取り専用 [`IColorFormat`](/slides/python-net/ja/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/ja/aspose.slides/baseportionformat/underline_line_format/) | 下線のアウトラインに使用される LineFormat プロパティを返します。継承は適用されません。<br/>            読み取り専用 [`ILineFormat`](/slides/python-net/ja/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/ja/aspose.slides/baseportionformat/underline_fill_format/) | 下線の FillFormat プロパティを返します。継承は適用されません。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/ja/aspose.slides/baseportionformat/font_bold/) | フォントが太字かどうかを決定します。継承は適用されません。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/ja/aspose.slides/baseportionformat/font_italic/) | フォントがイタリック体かどうかを決定します。継承は適用されません。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/ja/aspose.slides/baseportionformat/kumimoji/) | 数字がテキストの東アジア言語固有の縦書きレイアウトを無視すべきかを決定します。継承は適用されません。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/ja/aspose.slides/baseportionformat/normalise_height/) | テキストの高さを正規化すべきかどうかを決定します。継承は適用されません。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/ja/aspose.slides/baseportionformat/proof_disabled/) | テキストを校正しないかどうかを決定します。継承は適用されません。<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/ja/aspose.slides/baseportionformat/font_underline/) | テキストの下線タイプを取得または設定します。継承は適用されません。<br/>            読み書き [`TextUnderlineType`](/slides/python-net/ja/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ja/aspose.slides/baseportionformat/text_cap_type/) | テキストの大文字化タイプを取得または設定します。継承は適用されません。<br/>            読み書き [`TextCapType`](/slides/python-net/ja/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ja/aspose.slides/baseportionformat/strikethrough_type/) | テキストの取り消し線タイプを取得または設定します。継承は適用されません。<br/>            読み書き [`TextStrikethroughType`](/slides/python-net/ja/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/ja/aspose.slides/baseportionformat/is_hard_underline_line/) | 下線スタイルが独自の LineFormat プロパティを持つか、継承するか<br/>            テキストの LineFormat プロパティから<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/ja/aspose.slides/baseportionformat/is_hard_underline_fill/) | 下線スタイルが独自の FillFormat プロパティを持つか、継承するか<br/>            テキストの FillFormat プロパティから<br/>            読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/ja/aspose.slides/baseportionformat/font_height/) | 部分のフォント高さを取得または設定します。<br/>            **float.NaN** は高さが未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き **float**. |
| [`latin_font`](/slides/python-net/ja/aspose.slides/baseportionformat/latin_font/) | ラテン文字フォント情報を取得または設定します。<br/>            Null はフォントが未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ja/aspose.slides/baseportionformat/east_asian_font/) | 東アジアフォント情報を取得または設定します。<br/>            Null はフォントが未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ja/aspose.slides/baseportionformat/complex_script_font/) | 複合スクリプトフォント情報を取得または設定します。<br/>            Null はフォントが未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ja/aspose.slides/baseportionformat/symbol_font/) | シンボリックフォント情報を取得または設定します。<br/>            Null はフォントが未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ja/aspose.slides/baseportionformat/escapement/) | 上付き文字または下付き文字のテキストを取得または設定します。<br/>            値は -100%（下付き）から 100%（上付き）までです。<br/>            **float.NaN** は値が未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き **float**. |
| [`kerning_minimal_size`](/slides/python-net/ja/aspose.slides/baseportionformat/kerning_minimal_size/) | カーニングをオンにすべき最小フォントサイズを取得または設定します。<br/>            **float.NaN** は値が未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き **float**. |
| [`language_id`](/slides/python-net/ja/aspose.slides/baseportionformat/language_id/) | 校正言語の Id を取得または設定します。スペルチェックや文法チェックに使用されます。<br/>            読み書き **str**. |
| [`alternative_language_id`](/slides/python-net/ja/aspose.slides/baseportionformat/alternative_language_id/) | 代替言語の Id を取得または設定します。<br/>            読み書き **str**. |
| [`spacing`](/slides/python-net/ja/aspose.slides/baseportionformat/spacing/) | 文字間隔の増分を取得または設定します。<br/>            **float.NaN** は値が未定義であり、マスターから継承されるべきことを意味します。<br/>            読み書き **float**. |
| [`spell_check`](/slides/python-net/ja/aspose.slides/baseportionformat/spell_check/) | テキスト部分のスペルチェックが有効かどうかを示す値を取得または設定します。<br/>            このプロパティが false に設定されている場合、テキスト要素のスペルチェックは抑制されます。<br/>            true に設定すると、スペルチェックが許可されます。<br/>            デフォルト値は `false` です。 |
| [`slide`](/slides/python-net/ja/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/baseportionformat/presentation/) |  |


### 参照
* クラス [`BasePortionFormat`](/slides/python-net/ja/aspose.slides/baseportionformat)
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)