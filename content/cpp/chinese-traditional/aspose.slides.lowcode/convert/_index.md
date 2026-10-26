---
title: Convert
second_title: Aspose.Slides for C++ API 參考
description: 表示一組旨在轉換 Presentation 的方法。
type: docs
weight: 27
url: /zh-hant/aspose.slides.lowcode/convert/
---
## 轉換類別


表示一組旨在轉換 [Presentation](../../aspose.slides/presentation/) 的方法。

```cpp
class Convert
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | 使用傳入的輸出路徑副檔名來確定所需的導出格式，將 [Presentation](../../aspose.slides/presentation/) 轉換。 |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 將輸入簡報轉換為一組 JPEG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 將輸入簡報轉換為一組 JPEG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 將輸入簡報轉換為一組 JPEG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.jpeg"，結果將儲存為一組 "myPath/myFilename_N.jpeg" 檔案，其中 N 為投影片編號。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 PDF。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 PDF。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 PDF。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 PDF。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 將輸入簡報轉換為一組 PNG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 將輸入簡報轉換為一組 PNG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 將輸入簡報轉換為一組 PNG 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.png"，結果將儲存為一組 "myPath/myFilename_N.png" 檔案，其中 N 為投影片編號。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 SVG。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 將 [Presentation](../../aspose.slides/presentation/) 轉換為 SVG。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 將輸入簡報轉換為一組 TIFF 格式的圖像。  

 如果輸出檔案名稱為 "myPath/myFilename.tiff"，結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | 將輸入簡報轉換為 TIFF 格式，並使用自訂選項。若輸出檔案名稱為 "myPath/myFilename.tiff" 且 *multipage* 為 **false**，結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。否則，若 *multipage* 為 **true**，結果將是一個多頁的 "myPath/myFilename.tiff" 文件。 |

## 型別定義

| 型別別名 | 說明 |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | 將在每個 [Slide](../../aspose.slides/slide/) 上呼叫的回呼，預期返回輸出路徑。 |

## 備註



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## 另見

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)