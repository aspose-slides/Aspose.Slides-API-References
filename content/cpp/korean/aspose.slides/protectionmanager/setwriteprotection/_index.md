---
title: SetWriteProtection()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다.
type: docs
weight: 131
url: /ko/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) method

지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 비밀번호. |
## 비고

다음 샘플 코드는 프레젠테이션에 쓰기 보호를 설정하는 방법을 보여줍니다. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## 또 다른 항목

* Class [String](../../../system/string/)
* Class [ProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)