---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 경로와 생성 모드로 FileStream을 생성합니다.
type: docs
weight: 14
url: /ko/aspose.slides/streamwrapperfactory/createfilestreamwrapper/
---
## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) 메서드


지정된 경로와 생성 모드로 FileStream을 생성합니다.

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode) override
```

## StreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) 메서드


지정된 경로, 생성 모드 및 읽기/쓰기 권한으로 FileStream을 생성합니다.

```cpp
System::SharedPtr<IStreamWrapper> Aspose::Slides::StreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess) override
```

## 참조

* 열거형 [FileMode](../../../system.io/filemode/)
* 열거형 [FileAccess](../../../system.io/fileaccess/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IStreamWrapper](../../istreamwrapper/)
* 클래스 [String](../../../system/string/)
* 클래스 [StreamWrapperFactory](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)