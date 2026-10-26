---
title: AddEmbeddedFont()
second_title: Aspose.Slides for C++ API 참조
description: 임베디드 폰트를 추가합니다.
type: docs
weight: 105
url: /ko/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) 메서드

임베디드 폰트를 추가합니다.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | 폰트 데이터 객체 [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 임베디드 폰트 규칙 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 비고

폰트를 복사할 때 대부분의 폰트가 저작권이 있음을 명심하십시오. 먼저 폰트의 라이선스를 확인하고 해당 폰트를 다른 기기로 자유롭게 전송할 수 있는지 확인하십시오.

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) 메서드

임베디드 폰트를 추가합니다.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 폰트 데이터 **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | 임베디드 폰트 규칙 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## 비고

폰트를 추가할 때 대부분의 폰트가 저작권이 있음을 명심하십시오. 먼저 폰트의 라이선스를 확인하고 해당 폰트를 다른 기기로 자유롭게 전송할 수 있는지 확인하십시오.

## 참고

* 열거형 [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IFontData](../../ifontdata/)
* 클래스 [IFontsManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)