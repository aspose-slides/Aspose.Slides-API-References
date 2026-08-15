---
title: ToPng()
second_title: Aspose.Slides for C++ API 參考
description: 將輸入的簡報轉換為一組 PNG 格式的影像。  若將輸出檔名設定為 \"myPath/myFilename.png\"，結果將會儲存為一組 \"myPath/myFilename_N.png\" 檔案，其中 N 為投影片編號。
type: docs
weight: 53
url: /zh-hant/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) 方法

將輸入的簡報轉換為一組 PNG 格式的影像。

如果將輸出檔名設為 "myPath/myFilename.png"，結果將會儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) 方法

將輸入的簡報轉換為一組 PNG 格式的影像。

如果將輸出檔名設為 "myPath/myFilename.png"，結果將會儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 每個產生之影像的大小。 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) 方法

將輸入的簡報轉換為一組 PNG 格式的影像。

如果將輸出檔名設為 "myPath/myFilename.png"，結果將會儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出檔名。 |
| scale | **float** | 相對於原始投影片大小，套用於輸出影像的縮放比例。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 渲染選項。 |

## 備註

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)