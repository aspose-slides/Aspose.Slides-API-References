---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API 참조
description: 읽기 전용 권장 설정을 합니다. bool을 씁니다.
type: docs
weight: 92
url: /ko/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) 메서드

읽기 전용 권장 설정을 합니다. **bool**을 씁니다.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## 비고

다음 샘플 코드는 C#에서 [Aspose.Slides](../../)을 사용하여 PowerPoint [Presentation](../../presentation/)를 읽기 전용으로 설정하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [ProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)