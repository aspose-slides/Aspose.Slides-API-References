---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 79
url: /ja/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) メソッド

ストリームの現在のオブジェクトが表す位置を設定します。

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin** で指定された位置からのバイトオフセット |
| origin | [SeekOrigin](../../seekorigin/) | オフセットが計算される基準位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 参照

* 列挙型 [SeekOrigin](../../seekorigin/)
* クラス [BufferedStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)