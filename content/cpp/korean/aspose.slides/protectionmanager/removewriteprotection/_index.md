---
title: RemoveWriteProtection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 프레젠테이션에 대한 쓰기 보호를 제거합니다.
type: docs
weight: 144
url: /ko/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() 메서드


이 프레젠테이션에 대한 쓰기 보호를 제거합니다.

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## 비고


이 샘플 코드는 PowerPoint [Presentation](../../presentation/)에서 쓰기 보호를 제거하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [ProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)