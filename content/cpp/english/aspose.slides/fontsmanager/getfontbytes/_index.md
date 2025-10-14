---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves the byte array representing the font data for a specified font style and font data.
type: docs
weight: 131
url: /aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) method


Retrieves the byte array representing the font data for a specified font style and font data.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | The font data object containing the information about the font [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | The style of the font for which the data is to be retrieved [FontStyleType](../../fontstyletype/). |

### Return Value

A byte array containing the font data for the specified font style. If the font data or style is not found, returns null.
## Remarks




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, System::Drawing::FontStyle) method


Retrieves the byte array representing the font data for a specified font style and font data.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, System::Drawing::FontStyle fontStyle) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | The font data object containing the information about the font [FontData](../../fontdata/). |
| fontStyle | [System::Drawing::FontStyle](../../../system.drawing/fontstyle/) | The style of the font for which the data is to be retrieved [FontStyle](../../../system.drawing/fontstyle/). |

### Return Value

A byte array containing the font data for the specified font style. If the font data or style is not found, returns null.
## Remarks


Deprecated
:   Use GetFontBytes(IFontData fontData, FontStyleType fontStyle) method instead. This method will be removed after release of version 25.10.



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], System::Drawing::FontStyle::Regular);
```

## See Also

* Enum [FontStyleType](../../fontstyletype/)
* Enum [FontStyle](../../../system.drawing/fontstyle/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)