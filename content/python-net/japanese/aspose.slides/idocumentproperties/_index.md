---
title: IDocumentProperties class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/idocumentproperties/
---
## IDocumentProperties クラス

プレゼンテーションのプロパティを表します。

IDocumentProperties 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`app_version`](/slides/python-net/ja/aspose.slides/idocumentproperties/app_version/) | アプリのバージョンを返します。<br/>            読み取り専用 **str**. |
| [`name_of_application`](/slides/python-net/ja/aspose.slides/idocumentproperties/name_of_application/) | アプリケーションの名前を取得または設定します。<br/>            読み書き **str**. |
| [`company`](/slides/python-net/ja/aspose.slides/idocumentproperties/company/) | 会社プロパティを取得または設定します。<br/>            読み書き **str**. |
| [`manager`](/slides/python-net/ja/aspose.slides/idocumentproperties/manager/) | マネージャー プロパティを取得または設定します。<br/>            読み書き **str**. |
| [`presentation_format`](/slides/python-net/ja/aspose.slides/idocumentproperties/presentation_format/) | プレゼンテーションの意図された形式を取得または設定します。<br/>            読み書き **str**. |
| [`shared_doc`](/slides/python-net/ja/aspose.slides/idocumentproperties/shared_doc/) | プレゼンテーションが複数のユーザー間で共有されているかどうかを決定します。<br/>            読み書き **bool**. |
| [`application_template`](/slides/python-net/ja/aspose.slides/idocumentproperties/application_template/) | アプリケーションのテンプレートを取得または設定します。<br/>            読み書き **str**. |
| [`total_editing_time`](/slides/python-net/ja/aspose.slides/idocumentproperties/total_editing_time/) | プレゼンテーションの総編集時間。<br/>            読み書き **System.TimeSpan**. |
| [`title`](/slides/python-net/ja/aspose.slides/idocumentproperties/title/) | プレゼンテーションのタイトルを取得または設定します。<br/>            読み書き **str**. |
| [`subject`](/slides/python-net/ja/aspose.slides/idocumentproperties/subject/) | プレゼンテーションのサブジェクトを取得または設定します。<br/>            読み書き **str**. |
| [`author`](/slides/python-net/ja/aspose.slides/idocumentproperties/author/) | プレゼンテーションの作成者を取得または設定します。<br/>            読み書き **str**. |
| [`keywords`](/slides/python-net/ja/aspose.slides/idocumentproperties/keywords/) | プレゼンテーションのキーワードを取得または設定します。<br/>            読み書き **str**. |
| [`comments`](/slides/python-net/ja/aspose.slides/idocumentproperties/comments/) | プレゼンテーションのコメントを取得または設定します。<br/>            読み書き **str**. |
| [`category`](/slides/python-net/ja/aspose.slides/idocumentproperties/category/) | プレゼンテーションのカテゴリを取得または設定します。<br/>            読み書き **str**. |
| [`created_time`](/slides/python-net/ja/aspose.slides/idocumentproperties/created_time/) | プレゼンテーションが作成された日時を返します。<br/>            値は UTC です。<br/>            読み書き **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/ja/aspose.slides/idocumentproperties/last_saved_time/) | プレゼンテーションが最後に変更された日時を返します。<br/>            値は UTC です。<br/>            Presentation.DocumentProperties の場合は読み取り専用です (IPresentation オブジェクトの保存プロセス中に内部で更新されるため)。<br/>            メソッド [`IPresentationInfo.read_document_properties`](/slides/python-net/ja/aspose.slides/ipresentationinfo/read_document_properties) が返す DocumentProperties インスタンスを介して変更できます。<br/>            **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** メソッドの概要の例をご覧ください. |
| [`last_printed`](/slides/python-net/ja/aspose.slides/idocumentproperties/last_printed/) | プレゼンテーションが最後に印刷された日時を返します。<br/>            読み書き **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/ja/aspose.slides/idocumentproperties/last_saved_by/) | プレゼンテーションを最後に変更した人物の名前を取得または設定します。<br/>            読み書き **str**. |
| [`revision_number`](/slides/python-net/ja/aspose.slides/idocumentproperties/revision_number/) | プレゼンテーションのリビジョン番号を取得または設定します。<br/>            読み書き **int**. |
| [`content_status`](/slides/python-net/ja/aspose.slides/idocumentproperties/content_status/) | プレゼンテーションのコンテンツ状態を取得または設定します。<br/>            読み書き **str**. |
| [`content_type`](/slides/python-net/ja/aspose.slides/idocumentproperties/content_type/) | プレゼンテーションのコンテンツタイプを取得または設定します。<br/>            読み書き **str**. |
| [`hyperlink_base`](/slides/python-net/ja/aspose.slides/idocumentproperties/hyperlink_base/) | HyperlinkBase ドキュメントプロパティを取得または設定します。<br/>            読み書き **str**. |
| [`scale_crop`](/slides/python-net/ja/aspose.slides/idocumentproperties/scale_crop/) | ドキュメントサムネイルの表示モードを示します。<br/>            **true** に設定するとサムネイルがディスプレイに合わせて拡大縮小されます。<br/>            **false** に設定するとディスプレイに収まる部分だけが切り取られます。<br/>            読み書き **bool**. |
| [`links_up_to_date`](/slides/python-net/ja/aspose.slides/idocumentproperties/links_up_to_date/) | ドキュメント内のハイパーリンクが最新かどうかを示します。<br/>            **true** に設定するとハイパーリンクが更新されたことを示します。<br/>            **false** に設定するとハイパーリンクが古いことを示します。<br/>            読み書き **bool**. |
| [`hyperlinks_changed`](/slides/python-net/ja/aspose.slides/idocumentproperties/hyperlinks_changed/) | このパート内の 1 つ以上のハイパーリンクがプロデューサーによってこのパートでのみ更新されたことを指定します。<br/>            次にこのドキュメントを開くプロデューサーは、このパートで指定された新しいハイパーリンクでハイパーリンク関係を更新する必要があります。<br/>            読み書き **bool**. |
| [`slides`](/slides/python-net/ja/aspose.slides/idocumentproperties/slides/) | プレゼンテーションドキュメント内のスライド総数を指定します。<br/ja/>            読み取り専用 **int**. |
| [`hidden_slides`](/slides/python-net/ja/aspose.slides/idocumentproperties/hidden_slides/) | プレゼンテーションドキュメント内の非表示スライド数を指定します。<br/>            読み取り専用 **int**. |
| [`notes`](/slides/python-net/ja/aspose.slides/idocumentproperties/notes/) | ノートを含むプレゼンテーションのスライド数を指定します。<br/>            読み取り専用 **int**. |
| [`paragraphs`](/slides/python-net/ja/aspose.slides/idocumentproperties/paragraphs/) | 該当する場合、ドキュメント内に見つかった段落の総数を指定します。<br/>            読み取り専用 **int**. |
| [`words`](/slides/python-net/ja/aspose.slides/idocumentproperties/words/) | ドキュメントに含まれる単語の総数を指定します。<br/>            読み取り専用 **int**. |
| [`multimedia_clips`](/slides/python-net/ja/aspose.slides/idocumentproperties/multimedia_clips/) | ドキュメントに存在するサウンドまたはビデオ クリップの総数を指定します。<br/>            読み取り専用 **int**. |
| [`titles_of_parts`](/slides/python-net/ja/aspose.slides/idocumentproperties/titles_of_parts/) | 各ドキュメントパートのタイトルを指定します。<br/>            これらは実際のドキュメントパートではなく、ドキュメントセクションの概念的表現です。<br/>            読み取り専用 **List[str]**. |
| [`heading_pairs`](/slides/python-net/ja/aspose.slides/idocumentproperties/heading_pairs/) | ドキュメントパートのグループ化と各グループ内のパート数を示します。<br/>            読み取り専用 **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/ja/aspose.slides/idocumentproperties/count_of_custom_properties/) | コレクションに実際に含まれるカスタムプロパティの数を返します。<br/>            読み取り専用 **int**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付きブール値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き整数値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き DateTime 値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | カスタムプロパティから名前付き文字列値を取得します。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | 名前付きブール カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | 名前付き整数カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | 名前付き DateTime カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | 名前付き文字列カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 名前付き float カスタムプロパティを設定します。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/ja/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 名前付き double カスタムプロパティを設定します。 |
| [`get_custom_property_name(self, index)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_custom_property_name/#int) | 指定されたインデックスにあるカスタムプロパティ名を返します。 |
| [`remove_custom_property(self, name)`](/slides/python-net/ja/aspose.slides/idocumentproperties/remove_custom_property/#str) | 指定された名前に関連付けられたカスタムプロパティを削除します。 |
| [`contains_custom_property(self, name)`](/slides/python-net/ja/aspose.slides/idocumentproperties/contains_custom_property/#str) | 指定された名前のカスタムプロパティの存在をチェックします。 |
| [`clear_custom_properties(self)`](/slides/python-net/ja/aspose.slides/idocumentproperties/clear_custom_properties/#) | すべてのカスタムプロパティを削除します。 |
| [`clear_built_in_properties(self)`](/slides/python-net/ja/aspose.slides/idocumentproperties/clear_built_in_properties/#) | すべての組み込みプロパティをクリアし、デフォルト値に設定します。 |
| [`get_sensitivity_labels(self)`](/slides/python-net/ja/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | カスタムドキュメントプロパティ (Microsoft Information Protection SDK Metadata) から感度ラベルの配列を取得します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)