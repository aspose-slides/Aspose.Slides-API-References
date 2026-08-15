---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API 參考
description: 從投影片中擷取原始文字
type: docs
weight: 40
url: /zh-hant/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) 方法

Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 輸入檔案 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 擷取模式 |

### 返回值

包含表示原始投影片文字之 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) 方法

Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 擷取模式 |

### 返回值

包含表示原始投影片文字之 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) 方法

Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 擷取模式 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 返回值

包含表示原始投影片文字之 SlideText 陣列的 [PresentationText](../../presentationtext/) 實例

## 另見

* 列舉 [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPresentationText](../../ipresentationtext/)
* 類別 [String](../../../system/string/)
* 類別 [IPresentationFactory](../)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [ILoadOptions](../../iloadoptions/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)