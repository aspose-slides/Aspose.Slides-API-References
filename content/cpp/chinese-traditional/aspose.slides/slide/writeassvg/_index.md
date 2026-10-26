---
title: WriteAsSvg()
second_title: Aspose.Slides for C++ API 參考
description: 將投影片內容儲存為 SVG 檔案。
type: docs
weight: 157
url: /zh-hant/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) 方法


將投影片內容儲存為 SVG 檔案。

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目標串流 |
## 備註



以下程式碼範例示範如何將 PowerPoint 簡報的第一張投影片轉換為 SVG 檔案。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// 將第一張投影片儲存為 SVG 檔案
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) 方法


將投影片內容儲存為 SVG 檔案。

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 目標串流 |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 生成選項 |
## 備註



以下程式碼範例示範如何在使用選項的情況下，將 PowerPoint 簡報的第一張投影片轉換為 SVG 檔案。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// 將第一張投影片儲存為 SVG 檔案
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [Slide](../)
* 類別 [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)