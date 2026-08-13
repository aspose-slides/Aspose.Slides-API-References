---
title: set_PresentationLockingBehavior()
second_title: "Aspose.Slides for C++ API 참조"
description: "이 속성은 Presentation 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, 소스(스트림 또는 파일)는 Presentation 인스턴스 수명 동안 변경할 수 없습니다. 다음은 예시입니다:"
type: docs
weight: 14
url: /ko/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) 메서드


이 속성은 [Presentation](../../presentation/) 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, 소스(스트림 또는 파일)는 [Presentation](../../presentation/) 인스턴스 수명 동안 변경할 수 없습니다. 다음은 예시입니다:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## 비고



```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // IOException이 발생합니다. pres.pptx가 Presentation 수명 동안 잠겨 있기 때문입니다
    // File::Delete(u"pres.pptx");
}
// Presentation 객체가 파괴된 후, 파일이 잠금 해제되어 삭제할 수 있습니다
IO::File::Delete(u"pres.pptx");
```

## 참고

* 열거형 [PresentationLockingBehavior](../../presentationlockingbehavior/)
* 클래스 [IBlobManagementOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)