---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API リファレンス
description: メモリ内で全ての BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリにロードされます。この上限に達した場合にのみ、代替メカニズム（例えば一時ファイル）が使用されます。BLOB をメモリに保持することでパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。
type: docs
weight: 79
url: /ja/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() メソッド

メモリ内で全ての BLOB が占有できる最大合計サイズ（バイト単位）を定義します。既定では、すべての BLOB がメモリにロードされます。この上限に達した場合にのみ、代替メカニズム（一時ファイルなど）が使用されます。BLOB をメモリに保持することでパフォーマンスは最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## 備考

この値は [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) が false に設定されている場合は無視されます。メモリが唯一の保存場所となり、インメモリ BLOB の使用を制限しても効果がないためです。

既定値は 629,145,600 バイト（600 MB）です。

このプロパティをゼロに設定することもできますが、少量の最小メモリは依然として確保されます。

## 参照

* クラス [IBlobManagementOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)