---
title: BufferedStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 스트림을 래핑하고 4096바이트 길이의 버퍼를 사용하는 BufferedStream 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) 생성자

[BufferedStream](../) 객체를 생성하며, 지정된 스트림을 래핑하고 4096바이트 길이의 버퍼를 사용합니다.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 기본 [Stream](../../stream/) 객체 |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) 생성자

[BufferedStream](../) 객체를 생성하며, 지정된 스트림을 래핑하고 지정된 크기의 버퍼를 사용합니다.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 기본 [Stream](../../stream/) 객체 |
| bufferSize | int | 버퍼 크기(바이트) |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)