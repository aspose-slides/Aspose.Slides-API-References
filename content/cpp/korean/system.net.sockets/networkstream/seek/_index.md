---
title: Seek()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 183
url: /ko/system.net.sockets/networkstream/seek/
---
## NetworkStream::Seek(int64_t, IO::SeekOrigin) 메서드


현재 객체가 나타내는 스트림의 위치를 설정합니다.

```cpp
int64_t System::Net::Sockets::NetworkStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | **origin**에 의해 지정된 위치를 기준으로 하는 바이트 오프셋 |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | 오프셋이 계산되는 시작 위치와 방향을 지정합니다 |

### 반환값

스트림의 새로운 위치

## 관련 항목

* 열거형 [SeekOrigin](../../../system.io/seekorigin/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)