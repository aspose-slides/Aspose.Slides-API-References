---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/fontsmanager/
---
## FontsManager クラス

プレゼンテーション全体のフォントを管理します。

FontsManager タイプは次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ja/aspose.slides/fontsmanager/font_subst_rule_list/) | フォントの置換をレンダリング時に使用します。<br/>            読み書き [`IFontSubstRuleCollection`](/slides/python-net/ja/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ja/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | フォールバック機能による適切な置換のために、フォントのコレクションを管理するユーザーの FontFallBack ルールコレクションを表します。<br/>            読み書き [`IFontFallBackRulesCollection`](/slides/python-net/ja/aspose.slides/ifontfallbackrulescollection). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_substitutions/#) | プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。 |
| [`get_substitutions(self, slides)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_substitutions/#listint) | 指定されたスライドのレンダリング中に置き換えられるフォントに関する情報を取得します。 |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します<br/>            フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるか検証してください。フォントデータが None の場合やこのフォントがすでに埋め込まれている場合は ArgumentException がスローされる可能性があります |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ja/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 埋め込みフォントを追加します<br/>            フォントをコピーする際は、ほとんどのフォントが著作権で保護されていることに留意してください。事前にフォントのライセンスを確認し、別のマシンへ自由に転送できるか検証してください。フォントデータが None の場合やこのフォントがすでに埋め込まれている場合は ArgumentException がスローされる可能性があります |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ja/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | プレゼンテーション内のフォントを置換します |
| [`replace_font(self, subst_rule)`](/slides/python-net/ja/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | [`FontSubstRule`](/slides/python-net/ja/aspose.slides/fontsubstrule) で提供された情報を使用してプレゼンテーション内のフォントを置換します |
| [`replace_font(self, subst_rules)`](/slides/python-net/ja/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | [`FontSubstRule`](/slides/python-net/ja/aspose.slides/fontsubstrule) のコレクションで提供された情報を使用してプレゼンテーション内のフォントを置換します |
| [`get_fonts(self)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_fonts/#) | プレゼンテーションで使用されているフォントを返します |
| [`get_embedded_fonts(self)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_embedded_fonts/#) | プレゼンテーションに埋め込まれたフォントを返します |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ja/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | 埋め込みフォントを削除します |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 指定されたフォントスタイルとフォントデータに対するフォントデータを表すバイト配列を取得します。 |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ja/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | 指定されたバイト配列とフォント名からフォントの埋め込みレベルを判断します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)