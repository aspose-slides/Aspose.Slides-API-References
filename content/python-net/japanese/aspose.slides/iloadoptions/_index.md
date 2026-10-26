---
title: ILoadOptions class
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iloadoptions/
---
## ILoadOptions クラス

プレゼンテーションを読み込む際に、追加のオプション（例: フォーマットやデフォルトフォント）を指定できます。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`load_format`](/slides/python-net/ja/aspose.slides/iloadoptions/load_format/) | 読み込むプレゼンテーションのフォーマットを取得または設定します。<br/>            Read/write [`LoadFormat`](/slides/python-net/ja/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides/iloadoptions/default_regular_font/) | ソースフォントが見つからない場合に使用される標準フォントを取得または設定します。<br/>            Read-write **str**. |
| [`default_symbol_font`](/slides/python-net/ja/aspose.slides/iloadoptions/default_symbol_font/) | ソースフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。<br/>            Read-write **str**. |
| [`default_asian_font`](/slides/python-net/ja/aspose.slides/iloadoptions/default_asian_font/) | ソースフォントが見つからない場合に使用されるアジアフォントを取得または設定します。<br/>            Read-write **str**. |
| [`password`](/slides/python-net/ja/aspose.slides/iloadoptions/password/) | パスワードを取得または設定します。<br/>            Read-write **str**. |
| [`only_load_document_properties`](/slides/python-net/ja/aspose.slides/iloadoptions/only_load_document_properties/) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。<br/>            true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。<br/>            false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。<br/>            プレゼンテーションが暗号化されていない場合、プロパティの値は常に無視されます。<br/>            暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティをロードできず、例外がスローされます。<br/>            Read-write **bool**. |
| [`warning_callback`](/slides/python-net/ja/aspose.slides/iloadoptions/warning_callback/) | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            Read/write [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ja/aspose.slides/iloadoptions/blob_management_options/) | Binary Large Object（BLOB）の処理動作を管理するために使用できるオプションを表します。<br/>            たとえば、一時ファイルの使用やメモリ内の BLOB バイト数の上限などです。これらのオプションは、特定の環境や要件に対して最適なパフォーマンス/メモリ使用率のバランスを設定することを目的としています。<br/>            Binary Large Object（BLOB）とは、単一エンティティとして保存されるバイナリデータであり、たとえば音声、動画、またはプレゼンテーション自体になることがあります。 |
| [`document_level_font_sources`](/slides/python-net/ja/aspose.slides/iloadoptions/document_level_font_sources/) | プレゼンテーションで使用される外部フォントのソースを指定します。<br/>            これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションと共有されません。 |
| [`interruption_token`](/slides/python-net/ja/aspose.slides/iloadoptions/interruption_token/) | 割り込み要求を監視するトークンです。<br/>            <br/>            このトークンは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[`IInterruptionTokenSource`](/slides/python-net/ja/aspose.slides/iinterruptiontokensource) の [`IInterruptionTokenSource.interrupt`](/slides/python-net/ja/aspose.slides/iinterruptiontokensource/interrupt) メソッドを呼び出すことで中断されます。 |
| [`resource_loading_callback`](/slides/python-net/ja/aspose.slides/iloadoptions/resource_loading_callback/) | 外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/ja/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ja/aspose.slides/iloadoptions/spreadsheet_options/) | 追加のスプレッドシート動作を指定するために使用できるオプションを表します。 |
| [`default_text_language`](/slides/python-net/ja/aspose.slides/iloadoptions/default_text_language/) | プレゼンテーションテキストのデフォルト言語を取得または設定します。<br/>            Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ja/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | プレゼンテーションの読み込み時に Aspose.Slides が埋め込みバイナリオブジェクトをすべて削除するかどうかを決定します。<br/>            <br/>埋め込みバイナリオブジェクトのタイプ:<br/><br/><br/>* VBA プロジェクト [`IPresentation.vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project)<br/>* OLE オブジェクト埋め込みデータ [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX コントロールバイナリデータ [`IControl.active_x_control_binary`](/slides/python-net/ja/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)