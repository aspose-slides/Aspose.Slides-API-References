---
title: SystemIOStreamWrappingMode
second_title: Aspose.Slides for C++ API 레퍼런스
description: "래퍼가 System::IO::Stream와 유사한 스트림에 대해 수행할 I/O 작업 모드를 지정합니다."
type: docs
weight: 599
url: /ko/system.io/systemiostreamwrappingmode/
---
## SystemIOStreamWrappingMode 열거형

래퍼가 [System::IO::Stream](../stream/)와 유사한 스트림에 대해 수행할 I/O 작업 모드를 지정합니다.

```cpp
enum class SystemIOStreamWrappingMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Binary | 0 | 입력 작업이 스트림 바이트를 char_type 데이터로 인코딩하고, 출력 작업이 char_type 데이터를 스트림 바이트로 디코딩할 수 있게 하는 모드입니다. |
| Conversion | 1 | 입력 작업이 스트림 바이트를 **uint8_t** 타입에서 char_type 타입으로, 출력 작업이 그 역으로 변환할 수 있게 하는 모드입니다. |

## 참고

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)