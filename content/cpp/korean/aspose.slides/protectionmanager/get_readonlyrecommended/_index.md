---
title: get_ReadOnlyRecommended()
second_title: C++용 Aspose.Slides API 참조
description: 읽기 전용 권장 사항을 가져옵니다. 읽기 bool.
type: docs
weight: 79
url: /ko/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() 메서드


읽기 전용 권장 사항을 가져옵니다. 읽기 **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## 비고


다음 샘플 코드는 [Presentation](../../presentation/) PowerPoint를 C#에서 [Aspose.Slides](../../)를 사용하여 읽기 전용으로 설정하는 방법을 보여줍니다. 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [ProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)