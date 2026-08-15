---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API 參考文件
description: 從投影片中取得原始文字
type: docs
weight: 53
url: /zh-hant/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method

從投影片中取得原始文字

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 輸入檔案 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽取模式 |

### 返回值

包含表示原始投影片文字的 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method

從投影片中取得原始文字

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽取模式 |

### 返回值

包含表示原始投影片文字的 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method

從投影片中取得原始文字

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 抽取模式 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 返回值

包含表示原始投影片文字的 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## 另請參見

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)