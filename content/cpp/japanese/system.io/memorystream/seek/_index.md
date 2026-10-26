---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 105
url: /ja/system.io/memorystream/seek/
---
## MemoryStream::Seek(int64_t, SeekOrigin) method

現在のオブジェクトが表すストリームの位置を設定します。

```cpp
int64_t System::IO::MemoryStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin** で指定された位置からのバイトオフセット |
| origin | [SeekOrigin](../../seekorigin/) | オフセットが計算される基準位置と方向を指定します |

### Return Value

ストリームの新しい位置

## See Also

* 列挙型 [SeekOrigin](../../seekorigin/)
* クラス [MemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)