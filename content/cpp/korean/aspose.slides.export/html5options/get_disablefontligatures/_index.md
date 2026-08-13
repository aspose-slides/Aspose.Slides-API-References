---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. true 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본값은 false 입니다.
type: docs
weight: 131
url: /ko/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() 메서드


텍스트가 리가처를 사용하지 않고 렌더링되는지 여부를 나타내는 값을 가져옵니다. **true** 로 설정하면 렌더링된 출력에서 리가처가 비활성화됩니다. 기본값은 **false** 입니다.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## 비고


예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 텍스트 렌더링에서 리가처 비활성화

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 참고

* 클래스 [Html5Options](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)