---
title: TransformBlock()
second_title: Aspose.Slides C++용 API 참조
description: 데이터 블록을 처리하고 출력 배열에 복사합니다.
type: docs
weight: 66
url: /ko/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) 메서드

데이터 블록을 처리하고 출력 배열에 복사합니다.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 데이터를 읽기 위해. |
| inputOffset | int | 입력 버퍼 오프셋. |
| inputCount | int | 처리할 바이트 수. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 복사할 출력 버퍼; 복사를 하지 않으려면 nullptr. |
| outputOffset | int | 출력 버퍼 오프셋. |

### 반환값

작성된 바이트 수.

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [HashAlgorithm](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)