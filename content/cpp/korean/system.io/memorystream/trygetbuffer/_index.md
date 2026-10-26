---
title: TryGetBuffer()
second_title: Aspose.Slides for C++ API 참조
description: 이 스트림이 생성된 부호 없는 바이트 배열을 반환합니다.
type: docs
weight: 170
url: /ko/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) 메서드


이 스트림이 생성된 부호 없는 바이트 배열을 반환합니다.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | 바이트 배열 - 출력 매개변수. 이 메서드가 true를 반환하면 이 스트림이 생성된 바이트 배열 세그먼트가 반환됩니다; 이 메서드가 false를 반환하면 이 매개변수는 기본값으로 설정됩니다. |

### 반환값

변환이 성공하면 true를 반환합니다.

## 참고

* 클래스 [ArraySegment](../../../system/arraysegment/)
* 클래스 [MemoryStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)