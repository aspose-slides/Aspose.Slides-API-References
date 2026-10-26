---
title: ToJpeg()
second_title: Aspose.Slides for C++ API 參考
description: 將輸入的簡報轉換為一組 JPEG 格式的影像。如果將輸出檔名指定為 \"myPath/myFilename.jpeg\"，結果將儲存為一組 \"myPath/myFilename_N.jpeg\" 檔案，其中 N 為投影片編號。
type: docs
weight: 40
url: /zh-hant/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) 方法

將輸入的簡報轉換為一組 JPEG 格式的影像。  

如果將輸出檔名指定為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) 方法

將輸入的簡報轉換為一組 JPEG 格式的影像。  

如果將輸出檔名指定為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 每個產生之影像的大小。 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) 方法

將輸入的簡報轉換為一組 JPEG 格式的影像。  

如果將輸出檔名指定為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |
| scale | **float** | 相對於原始投影片大小，套用於輸出影像的縮放比例。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 呈現選項。 |
## 備註




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [String](../../../system/string/)
* 類別 [Convert](../)
* 類別 [Size](../../../system.drawing/size/)
* 類別 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)