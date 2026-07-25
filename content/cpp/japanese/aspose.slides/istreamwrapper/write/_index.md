---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のストリームにバイト列を書き込み、書き込まれたバイト数分だけこのストリーム内の現在位置を進めます。
type: docs
weight: 144
url: /ja/aspose.slides/istreamwrapper/write/
---
## IStreamWrapper::Write(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) メソッド

現在のストリームにバイト列を書き込み、書き込まれたバイト数分だけこのストリーム内の現在位置を進めます。

```cpp
virtual void Aspose::Slides::IStreamWrapper::Write(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | **uint8_t** の配列 |
| offset | **int32_t** | バッファ内の 0 ベースのバイトオフセットで、現在のストリームへバイトをコピーし始める位置 **int32_t** |
| count | **int32_t** | 現在のストリームに書き込まれるバイト数 **int32_t** |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IStreamWrapper](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)