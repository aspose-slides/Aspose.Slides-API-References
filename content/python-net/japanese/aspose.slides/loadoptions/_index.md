---
title: LoadOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/loadoptions/
---
## LoadOptions クラス

プレゼンテーションの読み込み時に、追加オプション（フォーマットやデフォルトフォントなど）を指定できます。

LoadOptions 型は次のメンバーを公開します。

## コンストラクター

| コンストラクター | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/loadoptions/__init__/#) | 新しいデフォルトのロードオプションを作成します。 |
| [`__init__(self, load_format)`](/slides/python-net/ja/aspose.slides/loadoptions/__init__/#loadformat) | 新しいロードオプションを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`load_format`](/slides/python-net/ja/aspose.slides/loadoptions/load_format/) | ロードするプレゼンテーションのフォーマットを取得または設定します。<br/>            読み取り/書き込み [`LoadFormat`](/slides/python-net/ja/aspose.slides/loadformat)。 |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides/loadoptions/default_regular_font/) | 元のフォントが見つからない場合に使用される標準フォントを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`default_symbol_font`](/slides/python-net/ja/aspose.slides/loadoptions/default_symbol_font/) | 元のフォントが見つからない場合に使用されるシンボルフォントを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`default_asian_font`](/slides/python-net/ja/aspose.slides/loadoptions/default_asian_font/) | 元のフォントが見つからない場合に使用されるアジアフォントを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`password`](/slides/python-net/ja/aspose.slides/loadoptions/password/) | パスワードを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`only_load_document_properties`](/slides/python-net/ja/aspose.slides/loadoptions/only_load_document_properties/) | このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味を持ちます。<br/>            true の場合、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視されます。<br/>            false の場合、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードします。<br/>            プレゼンテーションが暗号化されていない場合、このプロパティの値は常に無視されます。<br/>            暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティをロードできず、例外がスローされます。<br/>            読み取り/書き込み **bool**。 |
| [`warning_callback`](/slides/python-net/ja/aspose.slides/loadoptions/warning_callback/) | 警告を受け取り、読み込み処理を継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback)。 |
| [`blob_management_options`](/slides/python-net/ja/aspose.slides/loadoptions/blob_management_options/) | Binary Large Objects (BLOB) の取り扱い動作を管理するために使用できるオプションを表します。たとえば、一時ファイルの使用やメモリ内の BLOB の最大バイト数などです。これらのオプションは、特定の環境や要件に対して最適なパフォーマンスとメモリ使用量のバランスを設定することを目的としています。Binary Large Object (BLOB) は単一のエンティティとして格納されたバイナリデータであり、たとえばオーディオ、ビデオ、またはプレゼンテーション自体になることがあります。 |
| [`document_level_font_sources`](/slides/python-net/ja/aspose.slides/loadoptions/document_level_font_sources/) | プレゼンテーションで使用される外部フォントのソースを指定します。<br/>            これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションとは共有されません。 |
| [`interruption_token`](/slides/python-net/ja/aspose.slides/loadoptions/interruption_token/) | 割り込み要求を監視するトークン。<br/>            <br/>            このトークンは [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンス全体のライフタイムを管理します。プレゼンテーションの読み込みや保存などの長時間実行される操作は、[`InterruptionTokenSource`](/slides/python-net/ja/aspose.slides/interruptiontokensource) の [`InterruptionTokenSource.interrupt`](/slides/python-net/ja/aspose.slides/interruptiontokensource/interrupt) メソッドを呼び出すことで割り込まれます。 |
| [`resource_loading_callback`](/slides/python-net/ja/aspose.slides/loadoptions/resource_loading_callback/) | 外部リソースのロードを管理するコールバックインターフェイスを取得または設定します。<br/>            読み取り/書き込み [`IResourceLoadingCallback`](/slides/python-net/ja/aspose.slides/iresourceloadingcallback)。 |
| [`spreadsheet_options`](/slides/python-net/ja/aspose.slides/loadoptions/spreadsheet_options/) | スプレッドシート用のオプションを取得します。例えば、これらのオプションはチャートの数式計算に影響します。 |
| [`default_text_language`](/slides/python-net/ja/aspose.slides/loadoptions/default_text_language/) | プレゼンテーションテキストのデフォルト言語を取得または設定します。<br/>             読み取り/書き込み **str**。 |
| [`delete_embedded_binary_objects`](/slides/python-net/ja/aspose.slides/loadoptions/delete_embedded_binary_objects/) | プレゼンテーションの読み込み時に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。<br/>            <br/>埋め込みバイナリオブジェクトのタイプ:<br/><br/><br/>* VBA プロジェクト [`IPresentation.vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project)<br/>* OLE オブジェクト埋め込みデータ [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX コントロールバイナリデータ [`IControl.active_x_control_binary`](/slides/python-net/ja/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            読み取り/書き込み **bool**。 |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)