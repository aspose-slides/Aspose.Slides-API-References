---
title: Seek()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 157
url: /ko/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) 메서드

현재 객체가 나타내는 스트림의 위치를 설정합니다.

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | **origin**에 의해 지정된 위치를 기준으로 하는 바이트 오프셋 |
| loc | [SeekOrigin](../../seekorigin/) | 오프셋이 계산되는 시작 위치와 방향을 지정합니다 |

### 반환값

스트림의 새 위치

## 참고

* 열거형 [SeekOrigin](../../seekorigin/)
* 클래스 [UnmanagedMemoryStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)