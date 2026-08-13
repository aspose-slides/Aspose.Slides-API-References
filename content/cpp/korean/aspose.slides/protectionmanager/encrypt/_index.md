---
title: Encrypt()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 비밀번호로 프레젠테이션을 암호화합니다.
type: docs
weight: 105
url: /ko/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) 메서드

지정된 비밀번호로 [Presentation](../../presentation/)를 암호화합니다.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | 비밀번호. |

## 비고

다음 샘플 코드는 PowerPoint [Presentation](../../presentation/)를 암호화하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ProtectionManager](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)