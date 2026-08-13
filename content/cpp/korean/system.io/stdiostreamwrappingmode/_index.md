---
title: STDIOStreamWrappingMode
second_title: Aspose.Slides for C++ API 레퍼런스
description: "래퍼가 std::iostreams와 유사한 스트림에서 수행할 I/O 작업 모드를 지정합니다."
type: docs
weight: 573
url: /ko/system.io/stdiostreamwrappingmode/
---
## STDIOStreamWrappingMode 열거형

래퍼가 std::iostreams와 유사한 스트림에서 수행할 I/O 작업 모드를 지정합니다.

```cpp
enum class STDIOStreamWrappingMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Binary | 0 | 입력 작업이 char_type 타입의 스트림 데이터를 바이트로 디코딩하고, 출력 작업이 바이트를 char_type 데이터로 인코딩하도록 허용하는 모드입니다. |
| Conversion | 1 | 입력 작업이 char_type 타입의 스트림 데이터를 **uint8_t** 타입으로 변환하고, 출력 작업이 그 반대로 변환하도록 허용하는 모드입니다. |

## 참조

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)