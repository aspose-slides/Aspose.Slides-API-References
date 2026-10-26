---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 참조
description: 데이터의 마지막 블록을 처리하고 출력 값을 계산합니다.
type: docs
weight: 66
url: /ko/system.security.cryptography/tobase64transform/transformfinalblock/
---
## ToBase64Transform::TransformFinalBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) method

데이터의 마지막 블록을 처리하고 출력 값을 계산합니다.

```cpp
System::ArrayPtr<uint8_t> System::Security::Cryptography::ToBase64Transform::TransformFinalBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 데이터를 읽기 위해. |
| inputOffset | **int32_t** | 입력 버퍼 오프셋. |
| inputCount | **int32_t** | 처리할 바이트 수. |

### 반환 값

전체 입력 시퀀스에 대해 계산된 출력.

## 또 보기

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ToBase64Transform](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)