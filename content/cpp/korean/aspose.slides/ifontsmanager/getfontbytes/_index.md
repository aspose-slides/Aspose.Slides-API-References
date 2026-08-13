---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 글꼴 스타일 및 글꼴 데이터에 대한 글꼴 데이터를 나타내는 바이트 배열을 검색합니다.
type: docs
weight: 131
url: /ko/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) 메서드

지정된 글꼴 스타일 및 글꼴 데이터에 대한 글꼴 데이터를 나타내는 바이트 배열을 검색합니다.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 글꼴 [IFontData](../../ifontdata/)에 대한 정보를 포함하는 글꼴 데이터 객체. |
| fontStyle | [FontStyleType](../../fontstyletype/) | 데이터를 검색할 글꼴 스타일 [FontStyleType](../../fontstyletype/). |

### 반환값

지정된 글꼴 스타일에 대한 글꼴 데이터를 포함하는 바이트 배열입니다. 글꼴 데이터 또는 스타일을 찾을 수 없으면 null을 반환합니다.

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 참조

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)