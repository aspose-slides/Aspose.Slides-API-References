---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API 參考文件
description: 擷取代表指定字型樣式與字型資料之字型資料的位元組陣列。
type: docs
weight: 131
url: /zh-hant/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) 方法


擷取代表指定字型樣式與字型資料之字型資料的位元組陣列。

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 包含關於字型 [IFontData](../../ifontdata/) 資訊的字型資料物件。 |
| fontStyle | [FontStyleType](../../fontstyletype/) | 要擷取資料的字型樣式 [FontStyleType](../../fontstyletype/)。 |

### 回傳值

包含指定字型樣式之字型資料的位元組陣列。若找不到字型資料或樣式，則傳回 null。
## 備註




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 另請參閱

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)