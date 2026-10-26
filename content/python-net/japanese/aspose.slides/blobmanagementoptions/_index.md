---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions クラス

BLOB の処理ルールやその他の BLOB 設定を管理するために使用できるオプションを表します。

BlobManagementOptions 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/__init__/#) | 新しいデフォルトの BLOB 管理オプションを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | このプロパティは、Presentation クラスのインスタンスがソース - ファイル<br/>            またはストリームの所有者になれるかどうかを定義します。インスタンスが所有者である場合、ソースはロックされます。これにより<br/>            BLOB を扱う際のメモリ消費とパフォーマンスが向上しますが、ソース（ストリームまたはファイル）<br/>            は Presentation のインスタンスの有効期間中に変更できなくなります。 |
| [`is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | このプロパティは、BLOB を扱う際に一時ファイルを作成できるかどうかを定義します。これにより<br/>            メモリ消費が大幅に減少しますが、ファイル作成の権限が必要です。<br/>            プレゼンテーションの作業が終了した後、すべてのファイルが削除されます。 |
| [`temp_files_root_path`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/temp_files_root_path/) | 一時ファイルが作成されるルートパスです。デフォルトではシステムの一時ディレクトリが使用されます。<br/>            ホスティングプロセスは、<br/>            そこにファイルとフォルダーを作成する権限を持つ必要があります。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | すべての BLOB がメモリ上で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB が<br/>            メモリにロードされます。この上限に達した場合にのみ、一時ファイルなどの代替手段が使用されます。BLOB をメモリに保持することでパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)