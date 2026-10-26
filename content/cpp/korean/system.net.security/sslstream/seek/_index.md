---
title: Seek()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 365
url: /ko/system.net.security/sslstream/seek/
---
## SslStream::Seek(int64_t, IO::SeekOrigin) 메서드

현재 개체가 나타내는 스트림의 위치를 설정합니다.

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | 바이트 오프셋이며 **origin**에 의해 지정된 위치를 기준으로 합니다 |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | 오프셋이 계산되는 기준 위치와 그 방향을 지정합니다 |

### 반환 값

스트림의 새로운 위치

## 참조

* 열거형 [SeekOrigin](../../../system.io/seekorigin/)
* 클래스 [SslStream](../)
* 네임스페이스 [System::Net::Security](../../)
* 라이브러리 [Aspose.Slides](../../../)