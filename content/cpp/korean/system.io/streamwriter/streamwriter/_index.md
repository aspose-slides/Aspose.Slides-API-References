---
title: StreamWriter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: UTF-8 인코딩 및 기본 크기 1024바이트인 버퍼를 사용하여 지정된 기본 스트림에 문자를 쓰는 StreamWriter 객체의 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 UTF-8 인코딩 및 기본 크기 1024바이트인 버퍼를 사용하여 지정된 기본 스트림에 문자를 씁니다.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 쓸 기본 스트림 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 지정된 인코딩과 기본 크기 1024바이트인 버퍼를 사용하여 지정된 기본 스트림에 문자를 씁니다.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 쓸 기본 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 지정된 인코딩과 지정된 크기의 버퍼를 사용하여 지정된 기본 스트림에 문자를 씁니다. 매개변수는 [StreamWriter](../) 객체가 처리될 때 기본 스트림을 닫을지 여부를 지정합니다.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 쓸 기본 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| buffer_size | int | 버퍼의 최소 크기(바이트) |
| leave_open | **bool** | 현재 [StreamWriter](../) 객체가 처리될 때 기본 스트림을 열어 둘지 여부를 지정합니다 |

## StreamWriter::StreamWriter(const String\&) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 UTF-8 인코딩 및 기본 크기 1024바이트인 버퍼를 사용하여 지정된 파일에 문자를 씁니다.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 문자를 쓸 파일의 경로 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 지정된 인코딩과 기본 크기 1024바이트인 버퍼를 사용하여 지정된 파일에 문자를 씁니다. 매개변수는 데이터를 파일에 추가할지 기존 파일을 덮어쓸지를 지정합니다.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 문자를 쓸 파일의 경로 |
| append | **bool** | 데이터를 지정된 파일에 추가할지(true) 아니면 파일을 덮어쓸지(false)를 지정합니다 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) 생성자

[StreamWriter](../) 객체의 인스턴스를 생성합니다. 이 객체는 지정된 인코딩과 버퍼 크기를 사용하여 지정된 파일에 문자를 씁니다. 매개변수는 데이터를 파일에 추가할지 기존 파일을 덮어쓸지를 지정합니다.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 문자를 쓸 파일의 경로 |
| append | **bool** | 데이터를 지정된 파일에 추가할지(true) 아니면 파일을 덮어쓸지(false)를 지정합니다 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| buffer_size | int | 사용할 버퍼 크기 |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [EncodingPtr](../../../system/encodingptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [StreamWriter](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)