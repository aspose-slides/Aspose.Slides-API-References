---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/
---
## IFontsManager クラス

Manages fonts across the presentation.

The IFontsManager type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ja/aspose.slides/ifontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering<br/>            読み取り/書き込み [`IFontSubstRuleCollection`](/slides/python-net/ja/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ja/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            読み取り/書き込み [`IFontFallBackRulesCollection`](/slides/python-net/ja/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/ja/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Registers whether registered fonts should be preferred over embedded fonts with the same font name and style.<br/>            有効にすると、エクスポート時に一致する埋め込みフォントが一時的に対応する登録済みフォントに置き換えられます。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_substitutions/#) | プレゼンテーションのレンダリング時に置換されるフォントに関する情報を取得します。 |
| [`get_substitutions(self, slides)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_substitutions/#listint) | 指定されたスライドのレンダリング中に置換されるフォントに関する情報を取得します。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します。<br/>            フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに注意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるか検証してください。フォントデータが None の場合や既に埋め込まれている場合は ArgumentException がスローされることがあります |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します。<br/>            フォントを追加する際は、ほとんどのフォントが著作権で保護されていることに注意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるか検証してください。フォントデータが None の場合や既に埋め込まれている場合は ArgumentException がスローされることがあります |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | プレゼンテーション内のフォントを置換します |
| [`replace_font(self, subst_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | [`IFontSubstRule`](/slides/python-net/ja/aspose.slides/ifontsubstrule) で提供される情報を使用してプレゼンテーション内のフォントを置換します |
| [`replace_font(self, subst_rules)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | [`IFontSubstRule`](/slides/python-net/ja/aspose.slides/ifontsubstrule) のコレクションで提供される情報を使用してプレゼンテーション内のフォントを置換します |
| [`get_fonts(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_fonts/#) | プレゼンテーションで使用されているフォントを返します |
| [`get_embedded_fonts(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_embedded_fonts/#) | プレゼンテーションに埋め込まれたフォントを返します |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ja/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 埋め込みフォントを削除します |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 指定されたフォントスタイルとフォントデータのフォントデータを表すバイト配列を取得します。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 指定されたバイト配列とフォント名からフォントの埋め込みレベルを判定します。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)