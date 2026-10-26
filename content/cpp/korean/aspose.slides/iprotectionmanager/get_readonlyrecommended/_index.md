---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API 참조
description: 읽기 전용 권장 설정을 가져옵니다. 읽기 bool.
type: docs
weight: 79
url: /ko/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() 메서드


읽기 전용 권장 설정을 가져옵니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [IProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)