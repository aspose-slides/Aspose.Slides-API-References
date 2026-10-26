---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 157
url: /ja/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) メソッド


現在のオブジェクトが表すストリームの位置を設定します。

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin**で指定された位置に対するバイトオフセット |
| loc | [SeekOrigin](../../seekorigin/) | オフセットが計算される起点となる位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 参照

* 列挙型 [SeekOrigin](../../seekorigin/)
* クラス [UnmanagedMemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)