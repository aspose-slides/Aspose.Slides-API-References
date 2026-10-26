---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 경로와 생성 모드로 FileStream을 생성합니다.
type: docs
weight: 14
url: /ko/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) 메서드

지정된 경로와 생성 모드로 FileStream을 생성합니다.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 파일 이름 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 파일 모드 [System::IO::FileMode](../../../system.io/filemode/) |

### 반환 값

COM 인터페이스 [IStreamWrapper](../../istreamwrapper/)에 대한 스트림 래퍼

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) 메서드

지정된 경로, 생성 모드 및 읽기/쓰기 권한으로 FileStream을 생성합니다.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 파일 이름 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 파일 모드 [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | 파일 액세스 [System::IO::FileAccess](../../../system.io/fileaccess/) |

### 반환 값

COM 인터페이스 [IStreamWrapper](../../istreamwrapper/)에 대한 스트림 래퍼

## 또한 보기

* 열거형 [FileMode](../../../system.io/filemode/)
* 열거형 [FileAccess](../../../system.io/fileaccess/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IStreamWrapper](../../istreamwrapper/)
* 클래스 [String](../../../system/string/)
* 클래스 [IStreamWrapperFactory](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)