---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API リファレンス
description: すべての BLOB がメモリ内で占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持することでパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。
type: docs
weight: 79
url: /ja/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() メソッド

メモリ内にすべての BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、一時ファイルなどの代替メカニズムが使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせた動作を調整してください。

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## 備考

この値は [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) が false に設定されている場合は無視されます。メモリが唯一利用可能な保存場所となり、メモリ内 BLOB の使用制限が効果を持たないためです。

既定値は 629,145,600 バイト（600 MB）です。

このプロパティを 0 に設定することもできますが、最小限のメモリは確保されたままです。

## 参照

* クラス [BlobManagementOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)