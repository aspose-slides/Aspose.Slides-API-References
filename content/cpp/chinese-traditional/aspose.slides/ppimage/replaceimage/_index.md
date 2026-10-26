---
title: ReplaceImage()
second_title: Aspose.Slides for C++ API 參考文件
description: 取代圖像資料。
type: docs
weight: 118
url: /zh-hant/aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) 方法

取代圖像資料。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IImage\>) 方法

取代圖像資料。注意：當 Image 為圖元檔時，將被光柵化。請改用 ReplaceImage(byte[])。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IImage> newImage) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IPPImage\>) 方法

取代圖像資料。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IPPImage> newImage) override
```

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [PPImage](../)
* 類別 [IImage](../../iimage/)
* 類別 [IPPImage](../../ippimage/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)