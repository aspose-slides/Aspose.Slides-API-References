---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すストリームの位置を設定します。
type: docs
weight: 40
url: /ja/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) method

現在のオブジェクトが表すストリームの位置を設定します。

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | **origin** で指定された位置に対するバイトオフセット |
| origin | [SeekOrigin](../../seekorigin/) | オフセットが計算される起点の位置と方向を指定します |

### 戻り値

ストリームの新しい位置

## 関連項目

* 列挙型 [SeekOrigin](../../seekorigin/)
* クラス [STDIOStreamWrapperBase](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)