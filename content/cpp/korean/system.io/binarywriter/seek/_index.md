---
title: Seek()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 79
url: /ko/system.io/binarywriter/seek/
---
## BinaryWriter::Seek(int, System::IO::SeekOrigin) 메서드

현재 객체가 나타내는 스트림의 위치를 설정합니다.

```cpp
int64_t System::IO::BinaryWriter::Seek(int offset, System::IO::SeekOrigin origin=System::IO::SeekOrigin::Begin)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offset | int | **origin**에 의해 지정된 위치를 기준으로 하는 바이트 오프셋 |
| origin | [System::IO::SeekOrigin](../../seekorigin/) | 오프셋이 계산되는 시작 위치와 방향을 지정합니다 |

### 반환 값

스트림의 새 위치

## 관련 항목

* Enum [SeekOrigin](../../seekorigin/)
* Class [BinaryWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)