---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 바이트 배열과 글꼴 이름으로부터 글꼴의 임베딩 레벨을 결정합니다.
type: docs
weight: 144
url: /ko/aspose.slides/ifontsmanager/getfontembeddingleist/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) 메서드

지정된 바이트 배열과 글꼴 이름으로부터 글꼴의 임베딩 레벨을 결정합니다.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 글꼴 데이터를 포함하는 바이트 배열입니다. |
| fontName | [System::String](../../../system/string/) | 글꼴의 이름입니다. |

### 반환값

지정된 글꼴의 임베딩 레벨을 반환합니다.

## 비고




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## 참고

* 열거형 [EmbeddingLevel](../../embeddinglevel/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IFontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)