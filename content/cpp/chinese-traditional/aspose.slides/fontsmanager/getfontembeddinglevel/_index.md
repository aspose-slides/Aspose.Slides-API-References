---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides for C++ API 參考文件
description: 從給定的位元組陣列和字型名稱確定字型的嵌入層級。
type: docs
weight: 144
url: /zh-hant/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) 方法


從給定的位元組陣列和字型名稱確定字型的嵌入層級。

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含字型資料的位元組陣列。 |
| fontName | [System::String](../../../system/string/) | 字型的名稱。 |

### 返回值

指定字型的嵌入層級。
## 備註




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## 另請參閱

* 列舉 [EmbeddingLevel](../../embeddinglevel/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [FontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)