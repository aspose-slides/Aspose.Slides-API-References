---
title: CipherMode
second_title: Aspose.Slides for C++ API 참조
description: 블록 암호 모드.
type: docs
weight: 885
url: /ko/system.security.cryptography/ciphermode/
---
## CipherMode 열거형

블록 암호 모드.

```cpp
enum class CipherMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| CBC | 1 | 암호 블록 체이닝은 현재 블록을 이전 블록과 결합하여 암호화를 강화합니다. |
| ECB | 2 | 블록 간 영향을 주지 않는 전자 코드북 모드; 암호화가 약해집니다. |
| OFB | 3 | 큰 입력 블록을 작은 조각으로 처리하는 출력 피드백 모드. |
| CFB | 4 | 큰 입력 블록을 작은 조각으로 처리하는 암호 피드백 모드. 왜곡 규칙은 OFB와 다릅니다. |
| CTS | 5 | Cipher text stealing 모드로, 마지막 두 블록을 제외한 모든 블록에 대해 CBC처럼 동작합니다. |

## 참고

* 네임스페이스 [System::Security::Cryptography](../)
* 라이브러리 [Aspose.Slides](../../)