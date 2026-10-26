---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트가 리가처(ligatures)를 사용하지 않고 렌더링되는지를 나타내는 값을 설정합니다. true 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 false 로 설정됩니다.
type: docs
weight: 339
url: /ko/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) 메서드


텍스트가 ligatures를 사용하지 않고 렌더링되는지를 나타내는 값을 설정합니다. **true** 로 설정하면, 렌더링 결과에서 ligatures가 비활성화됩니다. 기본적으로, 이 속성은 **false** 로 설정됩니다.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // 텍스트 렌더링에서 리가처를 비활성화합니다

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## 참조

* 클래스 [ISVGOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)