---
title: get_FontsManager()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 폰트 관리자를 반환합니다. 읽기 전용 IFontsManager.
type: docs
weight: 157
url: /ko/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() 메서드

폰트 관리자를 반환합니다. 읽기 전용 [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## 비고

다음 예제는 PowerPoint에 임베디드 폰트를 추가하는 방법을 보여줍니다 [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontsManager](../../ifontsmanager/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)