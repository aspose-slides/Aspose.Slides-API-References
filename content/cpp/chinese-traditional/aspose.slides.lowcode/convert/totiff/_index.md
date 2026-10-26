---
title: ToTiff()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 將輸入的簡報轉換為一組 TIFF 格式的圖像。若輸出檔名指定為 \"myPath/myFilename.tiff\"，結果將儲存為一組 \"myPath/myFilename_N.tiff\" 檔案，其中 N 為投影片編號。
type: docs
weight: 66
url: /zh-hant/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) method


將輸入的簡報轉換為一組 TIFF 格式的影像。 

如果輸出檔名給定為 "myPath/myFilename.tiff"，結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出的檔案名稱。 |
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) method


將輸入的簡報以自訂選項轉換為 TIFF 格式。若輸出檔名給定為 "myPath/myFilename.tiff" 且 *multipage* 為 **false**，結果將儲存為一組 "myPath/myFilename_N.tiff" 檔案，其中 N 為投影片編號。否則，若 *multipage* 為 **true**，結果將是一個多頁的 "myPath/myFilename.tiff" 文件。

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入的簡報。 |
| outputFileName | [System::String](../../../system/string/) | 輸出的檔案名稱。 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF 儲存選項。 |
| multipage | **bool** | 指定產生的 TIFF 文件是否為多頁。 |
## 備註




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [String](../../../system/string/)
* 類別 [Convert](../)
* 類別 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)