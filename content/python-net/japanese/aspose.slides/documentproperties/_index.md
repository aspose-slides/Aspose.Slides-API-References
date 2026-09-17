---
title: DocumentProperties class
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/documentproperties/
---
## DocumentProperties クラス

プレゼンテーションのプロパティを表します。

DocumentProperties 型は次のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/documentproperties/__init__/#) | クラス [`DocumentProperties`](/slides/python-net/ja/aspose.slides/documentproperties) の新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`app_version`](/slides/python-net/ja/aspose.slides/documentproperties/app_version/) | アプリのバージョンを返します。<br/>            読み取り専用 **str**. |
| [`name_of_application`](/slides/python-net/ja/aspose.slides/documentproperties/name_of_application/) | アプリケーションの名前を取得または設定します。<br/>            読み書き **str**. |
| [`company`](/slides/python-net/ja/aspose.slides/documentproperties/company/) | 会社プロパティを取得または設定します。<br/>            読み書き **str**. |
| [`manager`](/slides/python-net/ja/aspose.slides/documentproperties/manager/) | マネージャープロパティを取得または設定します。<br/>            読み書き **str**. |
| [`presentation_format`](/slides/python-net/ja/aspose.slides/documentproperties/presentation_format/) | プレゼンテーションの意図された形式を取得または設定します。<br/>            読み書き **str**. |
| [`shared_doc`](/slides/python-net/ja/aspose.slides/documentproperties/shared_doc/) | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。<br/>            読み書き **bool**. |
| [`application_template`](/slides/python-net/ja/aspose.slides/documentproperties/application_template/) | アプリケーションのテンプレートを取得または設定します。<br/>            読み書き **str**. |
| [`total_editing_time`](/slides/python-net/ja/aspose.slides/documentproperties/total_editing_time/) | プレゼンテーションの総編集時間です。<br/>            読み書き **System.TimeSpan**. |
| [`title`](/slides/python-net/ja/aspose.slides/documentproperties/title/) | プレゼンテーションのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`subject`](/slides/python-net/ja/aspose.slides/documentproperties/subject/) | プレゼンテーションの件名を取得または設定します。<br/>            読み書き **str**. |
| [`author`](/slides/python-net/ja/aspose.slides/documentproperties/author/) | プレゼンテーションの作成者を取得または設定します。<br/>            読み書き **str**. |
| [`keywords`](/slides/python-net/ja/aspose.slides/documentproperties/keywords/) | プレゼンテーションのキーワードを取得または設定します。<br/>            読み書き **str**. |
| [`comments`](/slides/python-net/ja/aspose.slides/documentproperties/comments/) | プレゼンテーションのコメントを取得または設定します。<br/>            読み書き **str**. |
| [`category`](/slides/python-net/ja/aspose.slides/documentproperties/category/) | プレゼンテーションのカテゴリを取得または設定します。<br/>            読み書き **str**. |
| [`created_time`](/slides/python-net/ja/aspose.slides/documentproperties/created_time/) | プレゼンテーションが作成された日付を返します。<br/>            値はUTCです。<br/>            読み書き **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/ja/aspose.slides/documentproperties/last_saved_time/) | プレゼンテーションが最終更新された日付を返します。<br/>            値はUTCです。<br/>            Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。<br/>            [`IPresentationInfo.read_document_properties`](/slides/python-net/ja/aspose.slides/ipresentationinfo/read_document_properties) メソッドが返す DocumentProperties インスタンスを通じて変更できます。<br/>            例については **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** メソッドの概要を参照してください。 |
| [`last_printed`](/slides/python-net/ja/aspose.slides/documentproperties/last_printed/) | プレゼンテーションが最後に印刷された日付を返します。<br/>            読み書き **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/ja/aspose.slides/documentproperties/last_saved_by/) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。<br/>            読み書き **str**. |
| [`revision_number`](/slides/python-net/ja/aspose.slides/documentproperties/revision_number/) | プレゼンテーションのリビジョン番号を取得または設定します。<br/>            読み書き **int**. |
| [`content_status`](/slides/python-net/ja/aspose.slides/documentproperties/content_status/) | プレゼンテーションのコンテンツステータスを取得または設定します。<br/>            読み書き **str**. |
| [`content_type`](/slides/python-net/ja/aspose.slides/documentproperties/content_type/) | プレゼンテーションのコンテンツタイプを取得または設定します。<br/>            読み書き **str**. |
| [`hyperlink_base`](/slides/python-net/ja/aspose.slides/documentproperties/hyperlink_base/) | HyperlinkBase ドキュメントプロパティを取得または設定します。<br/>            読み書き **str**. |
| [`count_of_custom_properties`](/slides/python-net/ja/aspose.slides/documentproperties/count_of_custom_properties/) | コレクションに実際に含まれるカスタムプロパティの数を返します。<br/>            読み取り専用 **int**. |
| [`scale_crop`](/slides/python-net/ja/aspose.slides/documentproperties/scale_crop/) | ドキュメントサムネイルの表示モードを示します。 <br/>            この要素を **true** に設定すると、ドキュメントサムネイルがディスプレイに合わせて拡大縮小されます。 <br/>            この要素を **false** に設定すると、ディスプレイに合わせて表示できるセクションのみが表示されるようにドキュメントサムネイルがトリミングされます。<br/>            読み書き **bool**. |
| [`links_up_to_date`](/slides/python-net/ja/aspose.slides/documentproperties/links_up_to_date/) | ドキュメント内のハイパーリンクが最新かどうかを示します。 <br/>            この要素を **true** に設定すると、ハイパーリンクが更新されたことを示します。 <br/>            この要素を **false** に設定すると、ハイパーリンクが古いことを示します。<br/>            読み書き **bool**. |
| [`hyperlinks_changed`](/slides/python-net/ja/aspose.slides/documentproperties/hyperlinks_changed/) | このパート内の 1 つ以上のハイパーリンクが、プロデューサーによってこのパート専用に更新されたことを示します。 <br/>            次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。<br/>            読み書き **bool**. |
| [`slides`](/slides/python-net/ja/aspose.slides/documentproperties/slides/) | プレゼンテーションドキュメント内のスライド総数を返します。<br/ja/>            読み取り専用 **int**. |
| [`hidden_slides`](/slides/python-net/ja/aspose.slides/documentproperties/hidden_slides/) | プレゼンテーションドキュメント内の非表示スライド数を返します。<br/>            読み取り専用 **int**. |
| [`notes`](/slides/python-net/ja/aspose.slides/documentproperties/notes/) | ノートを含むプレゼンテーションのスライド数を返します。<br/>            読み取り専用 **int**. |
| [`paragraphs`](/slides/python-net/ja/aspose.slides/documentproperties/paragraphs/) | 該当する場合、ドキュメント内に見つかった段落の総数を返します。<br/>            読み取り専用 **int**. |
| [`words`](/slides/python-net/ja/aspose.slides/documentproperties/words/) | ドキュメントに含まれる単語の総数を返します。<br/>            読み取り専用 **int**. |
| [`multimedia_clips`](/slides/python-net/ja/aspose.slides/documentproperties/multimedia_clips/) | ドキュメントに存在する音声またはビデオクリップの総数を返します。<br/>            読み取り専用 **int**. |
| [`titles_of_parts`](/slides/python-net/ja/aspose.slides/documentproperties/titles_of_parts/) | 各ドキュメントパートのタイトルを指定します。 <br/>            これらのパートはドキュメントパートではなく、ドキュメントセクションの概念的表現です。<br/>            読み取り専用 **List[str]**. |
| [`heading_pairs`](/slides/python-net/ja/aspose.slides/documentproperties/heading_pairs/) | ドキュメントパートのグループ化と各グループ内のパート数を示します。<br/>            読み取り専用 **List[IHeadingPair]**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付きブール値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き整数値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き文字列値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | 名前付きブールカスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-int) | 名前付き整数カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | 名前付き DateTime カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-str) | 名前付き文字列カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-float) | 名前付き float カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/documentproperties/set_custom_property_value/#str-float) | 名前付き double カスタムプロパティを設定します。 |
| [`get_custom_property_name(self, index)`](/slides/python-net/ja/aspose.slides/documentproperties/get_custom_property_name/#int) | 指定されたインデックスのカスタムプロパティ名を返します。 |
| [`remove_custom_property(self, name)`](/slides/python-net/ja/aspose.slides/documentproperties/remove_custom_property/#str) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [`contains_custom_property(self, name)`](/slides/python-net/ja/aspose.slides/documentproperties/contains_custom_property/#str) | 指定された名前のカスタムプロパティの存在を確認します。 |
| [`clear_custom_properties(self)`](/slides/python-net/ja/aspose.slides/documentproperties/clear_custom_properties/#) | すべてのカスタムプロパティを削除します。 |
| [`get_sensitivity_labels(self)`](/slides/python-net/ja/aspose.slides/documentproperties/get_sensitivity_labels/#) | カスタムドキュメントプロパティから感度ラベルの配列を取得します（Microsoft Information Protection SDK メタデータ）。 |
| [`clear_built_in_properties(self)`](/slides/python-net/ja/aspose.slides/documentproperties/clear_built_in_properties/#) | すべての組み込みプロパティをクリアし、デフォルト値を設定します。 |
| [`clone(self)`](/slides/python-net/ja/aspose.slides/documentproperties/clone/#) | 現在のオブジェクトをクローンします。 |
| [`clone_t(self)`](/slides/python-net/ja/aspose.slides/documentproperties/clone_t/#) | 現在のオブジェクトをクローンします。 |

### 参照
* クラス [`DocumentProperties`](/slides/python-net/ja/aspose.slides/documentproperties)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)