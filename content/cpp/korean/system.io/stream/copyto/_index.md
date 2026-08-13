---
title: CopyTo()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 스트림에 바이트를 복사합니다.
type: docs
weight: 209
url: /ko/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) 메서드

지정된 스트림에 바이트를 복사합니다.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) 데이터가 복사될 대상. |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) 메서드

지정된 스트림에 바이트를 복사하고, 지정된 버퍼 크기를 사용합니다.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) 데이터가 복사될 대상. |
| buffer_size | **int32_t** | 버퍼의 크기. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)