---
title: SaveAdd()
second_title: Aspose.Slides for C++ API 參考
description: 在先前呼叫 Save() 方法時指定的檔案或串流中加入一個影格。
type: docs
weight: 14
url: /zh-hant/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) 方法

在先前呼叫 [Save()](../save/) 方法時指定的檔案或串流中加入一個影格。

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的編碼器參數 |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) 方法

在先前呼叫 [Save()](../save/) 方法時指定的檔案或串流中加入一個影格。

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | 包含要加入之影格的 [Image](../) 物件 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的編碼器參數 |

## 另請參閱

* 型別別名 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)