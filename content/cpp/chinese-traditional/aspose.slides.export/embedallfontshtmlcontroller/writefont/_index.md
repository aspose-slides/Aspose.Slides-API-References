---
title: WriteFont()
second_title: Aspose.Slides for C++ API 參考
description: 將資料以 base64 形式寫入 HTML 文件本身
type: docs
weight: 105
url: /zh-hant/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) 方法

將資料以 base64 形式寫入 HTML 文件本身

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML 生成器 |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 要序列化的字型 |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | 替代字型（如果發生字型替換），null，否則 |
| fontStyle | [System::String](../../../system/string/) | 字型樣式 |
| fontWeight | [System::String](../../../system/string/) | 字型粗細 |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 字型資料 |

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IHtmlGenerator](../../ihtmlgenerator/)
* 類別 [IFontData](../../../aspose.slides/ifontdata/)
* 類別 [String](../../../system/string/)
* 類別 [EmbedAllFontsHtmlController](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)