---
title: Read()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 씁니다.
type: docs
weight: 183
url: /ko/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) 메서드


스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열에 씁니다.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열. |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer** 내의 0 기반 위치. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환값

읽은 바이트 수.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) 메서드


스트림에서 지정된 바이트 수를 읽고 이를 지정된 바이트 배열 보기에 씁니다.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | 읽은 바이트를 기록할 바이트 배열 보기. |
| offset | **int32_t** | 쓰기 시작 위치인 **buffer** 내의 0 기반 위치. |
| count | **int32_t** | 읽을 바이트 수. |

### 반환값

읽은 바이트 수.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [FileStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)