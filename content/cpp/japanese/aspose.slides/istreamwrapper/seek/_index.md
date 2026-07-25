---
title: Seek()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のストリーム内の位置を設定します
type: docs
weight: 131
url: /ja/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) メソッド


現在のストリーム内の位置を設定します

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offset | **int64_t** | origin パラメータ **int64_t** に相対するバイトオフセット |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | 新しい位置を取得するために使用される基準点を示す [System::IO::SeekOrigin](../../../system.io/seekorigin/) 型の値 |

### 戻り値

現在のストリーム内の新しい位置 **int64_t**

## 参照

* 列挙体 [SeekOrigin](../../../system.io/seekorigin/)
* クラス [IStreamWrapper](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)