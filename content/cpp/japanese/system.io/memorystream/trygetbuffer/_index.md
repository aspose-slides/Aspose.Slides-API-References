---
title: TryGetBuffer()
second_title: Aspose.Slides for C++ API リファレンス
description: このストリームが作成された元の符号なしバイト配列を返します。
type: docs
weight: 170
url: /ja/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) メソッド


このストリームが作成された元の符号なしバイト配列を返します。

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | バイト配列 - out パラメータ。 このメソッドが true を返す場合、このストリームが作成されたバイト配列セグメントが返されます。 メソッドが false を返す場合、このパラメータはデフォルトに設定されます。 |

### 戻り値

変換が成功した場合は true。

## 参照

* クラス [ArraySegment](../../../system/arraysegment/)
* クラス [MemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)