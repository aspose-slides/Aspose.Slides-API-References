---
title: ReplaceImage()
second_title: Aspose.Slides の C++ API リファレンス
description: 画像データを置き換えます。
type: docs
weight: 118
url: /ja/aspose.slides/ppimage/replaceimage/
---
## PPImage::ReplaceImage(System::ArrayPtr\<uint8_t\>) メソッド

画像データを置き換えます。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::ArrayPtr<uint8_t> newImageData) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IImage\>) メソッド

画像データを置き換えます。注意: Image がメタファイルの場合、ラスタライズされます。代わりに ReplaceImage(byte[]) を使用してください

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IImage> newImage) override
```

## PPImage::ReplaceImage(System::SharedPtr\<Aspose::Slides::IPPImage\>) メソッド

画像データを置き換えます。

```cpp
void Aspose::Slides::PPImage::ReplaceImage(System::SharedPtr<Aspose::Slides::IPPImage> newImage) override
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PPImage](../)
* Class [IImage](../../iimage/)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)