---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API リファレンス
description: すべての BLOB がメモリ内で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この上限に達した時点でのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。
type: docs
weight: 92
url: /ja/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) メソッド


このメソッドは、すべての BLOB がメモリ内で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この制限に達した時点でのみ、代替メカニズム（一時ファイルなど）が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## 備考


この値は [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、インメモリ BLOB 使用量の制限は効果がありません。

デフォルト値は 629,145,600 バイト (600 MB) です。

このプロパティをゼロに設定することもできますが、少量の最小メモリは依然として確保されます。 
## 参照

* クラス [BlobManagementOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)