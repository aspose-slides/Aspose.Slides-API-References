---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트가 리가처를 사용하지 않고 렌더링되는지를 나타내는 값을 설정합니다. true 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본적으로 이 속성은 false 로 설정됩니다.
type: docs
weight: 144
url: /ko/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) 메서드


텍스트를 리거처를 사용하지 않고 렌더링할지 여부를 나타내는 값을 설정합니다. **true** 로 설정하면 렌더링된 출력에서 리거처가 비활성화됩니다. 기본적으로 이 속성은 **false** 로 설정됩니다.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## 비고


예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 텍스트 렌더링에서 리가처 비활성화

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 참조

* 클래스 [IHtml5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)