---
title: FileStream()
second_title: Aspose.Slides for C++ API 참조
description: FileStream 클래스의 새 인스턴스를 생성하고 지정된 매개변수로 초기화합니다.
type: docs
weight: 1
url: /ko/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) 생성자


[FileStream](../) 클래스의 새 인스턴스를 생성하고 지정된 매개변수로 초기화합니다.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |
| mode | [FileMode](../../filemode/) | 파일을 여는 모드를 지정합니다. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) 생성자


[FileStream](../) 클래스의 새 인스턴스를 생성하고 지정된 매개변수로 초기화합니다.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |
| mode | [FileMode](../../filemode/) | 파일을 여는 모드를 지정합니다. |
| access | [FileAccess](../../fileaccess/) | 요청된 접근 유형 |
| share | [FileShare](../../fileshare/) | 다른 [FileStream](../) 객체가 열린 파일에 대해 갖는 접근 유형 |
| buffer_size | **int32_t** | 읽기 및 쓰기 작업 중 버퍼링되는 바이트 수 |
| options | [FileOptions](../../fileoptions/) | 추가 옵션 |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) 생성자


[FileStream](../) 클래스의 새 인스턴스를 생성하고 지정된 매개변수로 초기화합니다.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 열 파일의 경로 |
| mode | [FileMode](../../filemode/) | 파일을 여는 모드를 지정합니다. |
| access | [FileAccess](../../fileaccess/) | 요청된 접근 유형 |
| share | [FileShare](../../fileshare/) | 다른 [FileStream](../) 객체가 열린 파일에 대해 갖는 접근 유형 |
| buffer_size | **int32_t** | 읽기 및 쓰기 작업 중 버퍼링되는 바이트 수 |
| useAsync | **bool** | 비동기 I/O 또는 동기 I/O 사용 여부를 지정합니다. |

## 비고



기본 운영 체제가 비동기 I/O를 지원하지 않을 수 있습니다. 

## FileStream::FileStream(const FileStream\&) 생성자




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## 참조

* 열거형 [FileMode](../../filemode/)
* 열거형 [FileAccess](../../fileaccess/)
* 열거형 [FileShare](../../fileshare/)
* 열거형 [FileOptions](../../fileoptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [FileStream](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)