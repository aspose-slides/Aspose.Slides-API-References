---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 183
url: /ja/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) メソッド

現在のオブジェクトが表すストリームの位置を設定します。

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin** で指定された位置に対するバイトオフセット |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | オフセットが計算される起点の位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 参照

* 列挙型 [SeekOrigin](../../../system.io/seekorigin/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)