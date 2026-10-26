---
title: ResourceLoading()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 외부 리소스 로드를 조절하는 콜백 메서드입니다.
type: docs
weight: 1
url: /ko/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) 메서드

외부 리소스 로드를 조절하는 콜백 메서드입니다.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | 로드 중인 리소스 데이터 [IResourceLoadingArgs](../../iresourceloadingargs/). |

### 반환값

리소스 로드 결정 [ResourceLoadingAction](../../resourceloadingaction/).

## 관련 항목

* 열거형 [ResourceLoadingAction](../../resourceloadingaction/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IResourceLoadingArgs](../../iresourceloadingargs/)
* 클래스 [IResourceLoadingCallback](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)