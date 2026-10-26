---
title: Seek()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 스트림 내에서 위치를 설정합니다
type: docs
weight: 131
url: /ko/aspose.slides/istreamwrapper/seek/
---
## IStreamWrapper::Seek(int64_t, System::IO::SeekOrigin) 메서드

현재 스트림 내의 위치를 설정합니다

```cpp
virtual int64_t Aspose::Slides::IStreamWrapper::Seek(int64_t offset, System::IO::SeekOrigin origin)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| offset | **int64_t** | **int64_t** 형식의 origin 매개변수에 대한 바이트 오프셋 |
| origin | [System::IO::SeekOrigin](../../../system.io/seekorigin/) | 새 위치를 얻기 위해 사용되는 기준점을 나타내는 [System::IO::SeekOrigin](../../../system.io/seekorigin/) 형식의 값 |

### 반환값

현재 스트림 내의 새 위치 **int64_t**

## 참조

* 열거형 [SeekOrigin](../../../system.io/seekorigin/)
* 클래스 [IStreamWrapper](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)