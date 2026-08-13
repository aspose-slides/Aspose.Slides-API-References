---
title: StreamReader()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 기본 스트림에서 UTF-8 인코딩을 사용하고 기본 크기 1024바이트인 버퍼로 문자를 읽는 StreamReader 객체의 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 UTF-8 인코딩을 사용하고 기본 크기 1024바이트인 버퍼로 문자를 읽습니다.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 읽을 기본 스트림 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 UTF-8 인코딩을 사용하고 기본 크기 1024바이트인 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 읽을 기본 스트림 |
| detectEncodingFromByteOrderMarks | **bool** | 스트림 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 지정된 인코딩을 사용하고 기본 크기 1024바이트인 버퍼로 문자를 읽습니다.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 읽을 기본 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 지정된 인코딩을 사용하고 기본 크기 1024바이트인 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 읽을 기본 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| detectEncodingFromByteOrderMarks | **bool** | 스트림 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 지정된 인코딩을 사용하고 지정된 크기의 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 문자를 읽을 기본 스트림 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| detectEncodingFromByteOrderMarks | **bool** | 스트림 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |
| bufferSize | int | 버퍼의 최소 크기(바이트) |

## StreamReader::StreamReader(const System::String\&) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 파일에서 UTF-8 인코딩을 사용하고 기본 크기 4096바이트인 버퍼로 문자를 읽습니다.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 문자를 읽을 파일 경로 |

## StreamReader::StreamReader(const System::String\&, bool) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 파일에서 UTF-8 인코딩을 사용하고 기본 크기 4096바이트인 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 문자를 읽을 파일 경로 |
| detectEncodingFromByteOrderMarks | **bool** | 파일 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 파일에서 지정된 인코딩을 사용하고 기본 크기 4096바이트인 버퍼로 문자를 읽습니다.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 문자를 읽을 파일 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 기본 스트림에서 지정된 인코딩을 사용하고 기본 크기 4096바이트인 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 문자를 읽을 파일 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| detectEncodingFromByteOrderMarks | **bool** | 파일 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) 생성자

[StreamReader](../) 객체의 인스턴스를 생성합니다. 지정된 파일에서 지정된 인코딩을 사용하고 지정된 크기의 버퍼로 문자를 읽습니다. 매개변수는 바이트 순서 표시(BOM) 감지를 사용할지 여부를 지정합니다.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | 문자를 읽을 파일 경로 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 사용할 인코딩 |
| detectEncodingFromByteOrderMarks | **bool** | 파일 시작 부분에서 바이트 순서 표시를 찾을 경우 true, 그렇지 않으면 false |
| bufferSize | int | 버퍼의 최소 크기(바이트) |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [StreamReader](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)