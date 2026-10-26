---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 SVG 圖像保存為 EMF 檔案。
type: docs
weight: 66
url: /zh-hant/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 方法

將 SVG 圖像保存為 EMF 檔案。

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目標串流 |
## 備註

以下範例說明如何將 SVG 圖像保存為中繼檔。 
```cpp
// 建立新的 SVG 圖像
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// 將 SVG 圖像保存為中繼檔
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 此範例說明如何將 SVG 圖像作為中繼檔加入簡報的影像集合。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 建立新的 SVG 圖像
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// 將 SVG 圖像保存為中繼檔
svgImage->WriteAsEmf(memStream);
// 將中繼檔加入影像集合
pres->get_Images()->AddImage(memStream->ToArray());
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [SvgImage](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)