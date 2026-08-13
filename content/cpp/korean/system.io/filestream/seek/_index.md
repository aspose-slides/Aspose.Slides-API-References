---
title: Seek()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 현재 객체가 나타내는 스트림의 위치를 설정합니다.
type: docs
weight: 209
url: /ko/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) 메서드


현재 객체가 나타내는 스트림의 위치를 설정합니다.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | **origin**에 의해 지정된 위치를 기준으로 하는 바이트 오프셋입니다. |
| origin | [SeekOrigin](../../seekorigin/) | 오프셋이 계산되는 시작 위치와 그 방향을 지정합니다. |

### 반환값

스트림의 새로운 위치입니다.

## 관련 항목

* 열거형 [SeekOrigin](../../seekorigin/)
* 클래스 [FileStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)