---
title: MemoryStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: MemoryStream 클래스의 새 인스턴스를 초기 용량이 0인 상태로 생성합니다.
type: docs
weight: 1
url: /ko/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() 생성자

[MemoryStream](../) 클래스의 새 인스턴스를 초기 용량이 0인 상태로 생성합니다.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) 생성자

[MemoryStream](../) 클래스의 새 인스턴스를 생성합니다. 이 인스턴스는 지정된 크기의 메모리 버퍼를 기반으로 하는 스트림을 나타냅니다.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| capacity_ | int | 생성되는 객체가 나타내는 스트림과 연결된 메모리 버퍼의 바이트 단위 크기 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) 생성자

[MemoryStream](../) 클래스의 새 인스턴스를 생성합니다. 이 클래스는 지정된 메모리 버퍼에 연결된 메모리 스트림을 나타냅니다. 매개변수는 스트림이 쓰기 가능한지 여부를 지정합니다.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 생성되는 객체가 나타내는 스트림이 기반으로 할 메모리 버퍼로 사용할 바이트 배열 |
| writable | **bool** | 스트림이 쓰기 가능한지 여부를 지정합니다 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) 생성자

[MemoryStream](../) 클래스의 새 인스턴스를 생성합니다. 이 클래스는 지정된 인덱스에서 시작하여 지정된 개수만큼 요소를 포함하는 지정된 메모리 버퍼의 세그먼트에 연결된 메모리 스트림을 나타냅니다. 매개변수는 스트림이 쓰기 가능한지와 GetBytes() 메서드를 호출할 수 있는지를 지정합니다.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 생성되는 객체가 나타내는 스트림이 기반으로 할 메모리 버퍼로 사용할 바이트 배열의 세그먼트 |
| index | int | **content**에서 세그먼트가 시작되는 요소의 0 기반 인덱스 |
| count | int | 세그먼트에 포함된 **content** 요소의 개수 |
| writable | **bool** | 스트림이 쓰기 가능한지 여부를 지정합니다 |
| publiclyVisible | **bool** | 기본 메모리 버퍼를 GetByte() 메서드 호출자에게 제공할지 여부를 지정합니다 |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [MemoryStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)