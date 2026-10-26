---
title: LoadingStreamBehavior
second_title: Aspose.Slides for C++ API 레퍼런스
description: "메서드에 전달되는 System::IO::Stream은 바이너리 대용량 객체(BLOB)로 간주됩니다(IBlobManagementOptions 설명을 참조하세요). 이 열거형의 값은 메서드에 전달될 때 System::IO::Stream이 어떻게 처리되어야 하는지를 지정합니다. 요구 사항에 따라 가장 효율적인 동작을 제공하기 위해 다양한 결정을 내릴 수 있습니다."
type: docs
weight: 6735
url: /ko/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 열거형

[System::IO::Stream](../../system.io/stream/)가 메서드에 전달될 때는 바이너리 대용량 객체(BLOB)로 간주됩니다([IBlobManagementOptions](../iblobmanagementoptions/) 설명을 참고하세요). 이 열거형의 값은 [System::IO::Stream](../../system.io/stream/)가 메서드에 전달될 때 어떻게 처리되어야 하는지를 지정합니다. 요구 사항에 따라 가장 효율적인 동작을 제공하기 위해 다양한 결정을 내릴 수 있습니다.

```cpp
enum class LoadingStreamBehavior
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | 스트림은 끝까지 읽힌 후 해제됩니다 - 즉, 향후 [IPresentation](../ipresentation/) 인스턴스에서 이 스트림이 사용되지 않을 것이 보장됩니다. 클라이언트 코드에 의해 닫히거나 다른 방법으로 사용할 수 있습니다. |
| KeepLocked | 1 | 스트림은 [IPresentation](../ipresentation/) 객체 내부에 잠기게 되며, 즉 스트림의 소유권이 전달됩니다. [IPresentation](../ipresentation/) 객체는 이 객체가 자체적으로 해제될 때 스트림을 올바르게 해제할 책임이 있습니다. 이 동작은 큰 BLOB 파일(예: 대용량 비디오 또는 오디오 - [IBlobManagementOptions](../iblobmanagementoptions/) 설명을 참고) 을 직렬화해야 하고 해당 파일을 메모리에 로드하거나 성능 문제를 방지하고자 할 때 매우 유용합니다. 파일을 위해 [System::IO::FileStream](../../system.io/filestream/) 를 열고 메서드에 전달하면서 [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior 를 선택하면 됩니다. |

## 참조

* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)