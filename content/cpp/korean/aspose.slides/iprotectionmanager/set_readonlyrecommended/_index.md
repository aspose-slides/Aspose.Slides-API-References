---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 읽기 전용 권장 사항을 설정합니다. bool을 씁니다.
type: docs
weight: 92
url: /ko/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) method


읽기 전용 권장 사항을 설정합니다. **bool**을 씁니다.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [IProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)