---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용할 수이며 다른 프레젠테이션과 공유되지 않습니다.
type: docs
weight: 222
url: /ko/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) 메서드

프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다. 이 글꼴은 프레젠테이션 전체 수명 동안 사용할 수 있으며 다른 프레젠테이션과 공유되지 않습니다.

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/)와 함께 사용되는 사용자 정의 글꼴을 지정하는 방법을 보여줍니다.

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// 프레젠테이션 작업
// CustomFont1, CustomFont2 및 assets\fonts와 global\fonts 폴더 및 하위 폴더의 글꼴이 프레젠테이션에서 사용 가능합니다
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFontSources](../../ifontsources/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)