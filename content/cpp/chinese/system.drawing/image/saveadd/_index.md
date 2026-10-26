---
title: SaveAdd()
second_title: Aspose.Slides C++ API 参考
description: 向先前对 Save() 方法的调用中指定的文件或流添加帧。
type: docs
weight: 14
url: /zh/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) method

向先前对 [Save()](../save/) 方法的调用中指定的文件或流添加帧。

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的编码器参数 |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) method

向先前对 [Save()](../save/) 方法的调用中指定的文件或流添加帧。

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | 包含要添加的帧的 [Image](../) 对象 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的编码器参数 |

## 另请参阅

* 类型定义 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Image](../)
* 命名空间 [System::Drawing](../../)
* 库 [Aspose.Slides](../../../)