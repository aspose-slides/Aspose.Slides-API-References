---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides for C++ API 참조
description: UnmanagedMemoryStream의 새 인스턴스를 생성합니다.
type: docs
weight: 118
url: /ko/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) 생성자

새 인스턴스를 생성합니다 [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pointer | **uint8_t** * | 비관리 버퍼에 대한 포인터 |
| length | **int64_t** | 바이트 단위의 비관리 버퍼 크기 |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) 생성자

새 인스턴스를 생성합니다 [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pointer | **uint8_t** * | 비관리 버퍼에 대한 포인터 |
| length | **int64_t** | 바이트 단위의 비관리 버퍼 크기 |
| capacity | **int64_t** | 스트림에 할당된 전체 메모리 양 |
| access | [FileAccess](../../fileaccess/) | 스트림이 읽기 전용, 쓰기 전용 또는 둘 다인지 지정합니다 |

## 참고

* Enum [FileAccess](../../fileaccess/)
* 클래스 [UnmanagedMemoryStream](../)
* 네임스페이스 [System::IO](../../)
* Library [Aspose.Slides](../../../)