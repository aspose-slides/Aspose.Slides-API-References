---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory プロパティ
メモリ内にすべての BLOB が占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。

### 備考

[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) が false に設定されている場合、このプロパティは無視されます。メモリが唯一のストレージ位置となり、メモリ内 BLOB の使用制限に効果がないためです。

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
* クラス [`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)