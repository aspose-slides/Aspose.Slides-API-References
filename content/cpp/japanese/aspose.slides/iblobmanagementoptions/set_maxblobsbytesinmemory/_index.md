---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API リファレンス
description: すべての BLOB がメモリ上で占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、代替メカニズム（例: 一時ファイル）が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。
type: docs
weight: 92
url: /ja/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) メソッド

メモリ上にすべての BLOB が占有できる最大合計サイズ（バイト単位）を定義します。デフォルトでは、すべての BLOB がメモリにロードされます。この制限に達した場合にのみ、代替メカニズム（一時ファイルなど）が使用されます。BLOB をメモリに保持するとパフォーマンスが最大化されますが、メモリ使用量が増加する可能性があります。このプロパティを使用して、環境や要件に合わせて動作を調整してください。

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## 備考

この値は [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) が false に設定されている場合は無視されます。メモリが唯一利用可能なストレージ位置となり、メモリ内 BLOB の使用を制限しても効果がありません。

デフォルト値は 629,145,600 バイト（600 MB）です。

このプロパティを 0 に設定できますが、少量の最低メモリは依然として確保されます。

## 関連項目

* クラス [IBlobManagementOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)