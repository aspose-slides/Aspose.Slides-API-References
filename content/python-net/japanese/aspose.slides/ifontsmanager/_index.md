---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontsmanager/
---
## IFontsManager クラス

プレゼンテーション全体のフォントを管理します。

IFontsManager 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ja/aspose.slides/ifontsmanager/font_subst_rule_list/) | レンダリング時に使用するフォント置換<br/>            読み書き [`IFontSubstRuleCollection`](/slides/python-net/ja/aspose.slides/ifontsubstrulecollection)。 |
| [`font_fall_back_rules_collection`](/slides/python-net/ja/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | ユーザーの FontFallBack ルールのコレクションを表し、フォントのコレクションを管理してフォールバック機能による適切な置換を行います<br/>            読み書き [`IFontFallBackRulesCollection`](/slides/python-net/ja/aspose.slides/ifontfallbackrulescollection)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_substitutions/#) | プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。 |
| [`get_substitutions(self, slides)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_substitutions/#listint) | 指定したスライドのレンダリング中に置き換えられるフォントに関する情報を取得します。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します。<br/>            フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに留意してください。まずフォントのライセンスを<br/>            事前に確認し、別のマシンに自由に転送できるかを検証してください。フォントデータが None の場合や既に埋め込まれている場合は ArgumentException がスローされる可能性があります |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します。<br/>            フォントを追加する際は、ほとんどのフォントが著作権で保護されていることに留意してください。まずフォントのライセンスを<br/>            事前に確認し、別のマシンに自由に転送できるかを検証してください。フォントデータが None の場合や既に埋め込まれている場合は ArgumentException がスローされる可能性があります |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | プレゼンテーションのフォントを置換します |
| [`replace_font(self, subst_rule)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | [`IFontSubstRule`](/slides/python-net/ja/aspose.slides/ifontsubstrule) で提供された情報を使用してプレゼンテーションのフォントを置換します |
| [`replace_font(self, subst_rules)`](/slides/python-net/ja/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | [`IFontSubstRule`](/slides/python-net/ja/aspose.slides/ifontsubstrule) のコレクションで提供された情報を使用してプレゼンテーションのフォントを置換します |
| [`get_fonts(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_fonts/#) | プレゼンテーションで使用されているフォントを返します |
| [`get_embedded_fonts(self)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_embedded_fonts/#) | プレゼンテーションに埋め込まれたフォントを返します |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ja/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | 埋め込みフォントを削除します |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 指定されたフォントスタイルとフォントデータに対するフォントデータのバイト配列を取得します。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ja/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | 指定されたバイト配列とフォント名からフォントの埋め込みレベルを判定します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)