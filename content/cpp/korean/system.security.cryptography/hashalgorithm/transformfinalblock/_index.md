---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터의 마지막 블록을 처리하고 해시를 계산합니다.
type: docs
weight: 79
url: /ko/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) 메서드

데이터의 마지막 블록을 처리하고 해시를 계산합니다.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)를 읽기 위한. |
| inputOffset | int | 입력 버퍼 오프셋. |
| inputCount | int | 처리할 바이트 수. |

### 반환값

전체 데이터 시퀀스에 대해 계산된 해시.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [HashAlgorithm](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)