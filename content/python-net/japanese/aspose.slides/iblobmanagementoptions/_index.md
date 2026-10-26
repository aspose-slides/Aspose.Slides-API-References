---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions クラス

Binary Large Object (BLOB) は単一のエンティティとして保存されるバイナリデータであり、たとえば BLOB は音声、動画、またはプレゼンテーション自体になる可能性があります。BLOB を操作する際のメモリ使用量を最適化するために様々な手法が使用されます — プレゼンテーションに既に保存されているもの、または後からプログラムで追加されるものです。[`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions) を使用すると、[`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) インスタンスのライフタイムにおける BLOB の取り扱いに関するさまざまな動作側面を変更できます。

IBlobManagementOptions 型は以下のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | このプロパティは、Presentation クラスのインスタンスがインスタンスのライフタイム中にソース（ファイル<br/>            またはストリーム）の所有者となることができるかどうかを定義します。インスタンスが所有者である場合、ソースがロックされます。これにより、BLOB を操作する際のメモリ使用量とパフォーマンスが向上しますが、Presentation のインスタンスのライフタイム中はソース（ストリームまたはファイル）を変更できなくなります。これは例です： |
| [`is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | このプロパティは、BLOB を操作する際に一時ファイルを作成できるかどうかを定義します。一時ファイルはメモリ使用量を大幅に減少させますが、ファイル作成の権限が必要です。<br/>            プレゼンテーションの処理が完了した後、すべてのファイルは削除されます。 |
| [`temp_files_root_path`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | 一時ファイルが作成されるルートパスです。既定では System の一時ディレクトリが使用されます。<br/>            ホスティングプロセスは、そこにファイルやフォルダーを作成する権限を持っている必要があります。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | メモリ上で BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定ではすべての BLOB がメモリにロードされますが、この上限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。 |

### 参照
* クラス [`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)