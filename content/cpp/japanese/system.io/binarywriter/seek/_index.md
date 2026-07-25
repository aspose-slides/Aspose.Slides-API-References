---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 79
url: /ja/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) メソッド


現在のオブジェクトが表すストリームの位置を設定します。

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| offset | int | **origin**で指定された位置を基準としたバイトオフセット |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | オフセットが計算される開始位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 参照

* 列挙体 [SeekOrigin](../../seekorigin/)
* クラス [BinaryWriter](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)