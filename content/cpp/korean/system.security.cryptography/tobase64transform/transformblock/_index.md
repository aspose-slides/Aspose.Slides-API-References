---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 참조
description: 데이터 블록을 처리하고 데이터를 출력 배열에 복사합니다.
type: docs
weight: 53
url: /ko/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) 메서드

데이터 블록을 처리하고 데이터를 출력 배열에 복사합니다.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 데이터를 읽기 위해. |
| inputOffset | **int32_t** | 입력 버퍼 오프셋. |
| inputCount | **int32_t** | 처리할 바이트 수. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 복사할 출력 버퍼; 복사를 하지 않으려면 nullptr. |
| outputOffset | **int32_t** | 출력 버퍼 오프셋. |

### 반환값

작성된 바이트 수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ToBase64Transform](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)