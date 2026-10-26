---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 79
url: /ja/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) method


現在のオブジェクトが表すストリームの位置を設定します。

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin** で指定された位置からのバイトオフセット |
| origin | [SeekOrigin](../../seekorigin/) | オフセットを計算する基準位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 関連項目

* 列挙体 [SeekOrigin](../../seekorigin/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)