---
title: GetFontBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 글꼴 스타일 및 글꼴 데이터에 대한 글꼴 데이터를 나타내는 바이트 배열을 검색합니다.
type: docs
weight: 131
url: /ko/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) 메서드

지정된 글꼴 스타일 및 글꼴 데이터에 대한 글꼴 데이터를 나타내는 바이트 배열을 검색합니다.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | 글꼴 데이터 객체로서, [IFontData](../../ifontdata/)에 대한 정보를 포함합니다. |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | 데이터를 검색해야 하는 글꼴 스타일 [FontStyleType](../../fontstyletype/). |

### 반환값

지정된 글꼴 스타일에 대한 글꼴 데이터를 포함하는 바이트 배열입니다. 글꼴 데이터나 스타일을 찾을 수 없으면 null을 반환합니다.

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## 참조

* 열거형 [FontStyleType](../../fontstyletype/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontData](../../ifontdata/)
* 클래스 [FontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)