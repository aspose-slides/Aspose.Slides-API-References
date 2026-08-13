---
title: PresentationLockingBehavior
second_title: Aspose.Slides C++ API 레퍼런스
description: "IPresentation 소스(파일 또는 System::IO::Stream)를 로드하고 IPresentation 인스턴스로 작업할 때의 동작을 나타냅니다."
type: docs
weight: 6748
url: /ko/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 열거형

[IPresentation](../ipresentation/) 소스(파일 또는 [System::IO::Stream](../../system.io/stream/))를 로드하고 [IPresentation](../ipresentation/) 인스턴스와 작업할 때의 동작을 나타냅니다.

```cpp
enum class PresentationLockingBehavior
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| LoadAndRelease | 0 | [IPresentation](../ipresentation/) 생성자 실행 중에만 소스가 잠깁니다. |
| KeepLocked | 1 | [IPresentation](../ipresentation/) 인스턴스 전체 수명 동안, 폐기될 때까지 소스가 잠깁니다. |

## 비고

소스는 [IPresentation](../ipresentation/) 생성자에 전달되는 매개변수입니다. 아래 예제에서 소스는 "pres.pptx" 파일입니다:

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```

이 예제에서는 소스("pres.pptx" 파일)가 [IPresentation](../ipresentation/) 인스턴스 수명 동안 잠기게 되며, 즉 다른 프로세스에서 변경하거나 삭제할 수 없습니다.

## 참고

* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)