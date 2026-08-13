---
title: Seek()
second_title: Aspose.Slides C++ API 참조
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 79
url: /ko/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) 메서드

현재 객체가 나타내는 스트림의 위치를 설정합니다.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | **origin**에 의해 지정된 위치를 기준으로 하는 바이트 오프셋 |
| origin | [SeekOrigin](../../seekorigin/) | 오프셋이 계산되는 시작 위치와 방향을 지정합니다 |

### 반환 값

스트림의 새 위치

## 또 보기

* 열거형 [SeekOrigin](../../seekorigin/)
* 클래스 [BufferedStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)