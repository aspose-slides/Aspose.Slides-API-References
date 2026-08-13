---
title: TransformBlock()
second_title: Aspose.Slides for C++ API 참조
description: 데이터 블록을 처리하고 데이터를 출력 배열에 복사합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) 메서드

데이터 블록을 처리하고 데이터를 출력 배열에 복사합니다.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 읽을 데이터. |
| inputOffset | int | 입력 버퍼 오프셋. |
| inputCount | int | 처리할 바이트 수. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터를 복사할 출력 버퍼; 복사를 하지 않으려면 nullptr. |
| outputOffset | int | 출력 버퍼 오프셋. |

### 반환 값

작성된 바이트 수.

## 또 보기

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICryptoTransform](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)