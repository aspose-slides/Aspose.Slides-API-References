---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory プロパティ
すべての BLOB がメモリ上で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、代替メカニズム（一時ファイルなど）が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。

### 備考
[`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) が false に設定されている場合、このプロパティは無視されます。これは、メモリが唯一利用可能なストレージ場所となり、メモリ内 BLOB の使用を制限しても効果がないためです。

### 定義:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### 参照
* クラス [`BlobManagementOptions`](/slides/python-net/ja/aspose.slides/blobmanagementoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)