---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 참조
description: 데이터의 마지막 블록을 처리하고 출력 값을 계산합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) 메서드


데이터의 마지막 블록을 처리하고 출력 값을 계산합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 데이터를 읽기 위한 버퍼. |
| inputOffset | int | 입력 버퍼 오프셋. |
| inputCount | int | 처리할 바이트 수. |

### 반환 값

전체 입력 시퀀스에 대해 계산된 출력 값.

## 관련 항목

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICryptoTransform](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)