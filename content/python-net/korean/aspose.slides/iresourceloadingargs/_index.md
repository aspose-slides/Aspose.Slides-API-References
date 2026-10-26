---
title: IResourceLoadingArgs class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs 클래스

외부 리소스 로딩 인수에 대한 인터페이스.

IResourceLoadingArgs 타입은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`original_uri`](/slides/python-net/ko/aspose.slides/iresourceloadingargs/original_uri/) | 가져온 프레젠테이션에 지정된 리소스의 원본 URI. |
| [`uri`](/slides/python-net/ko/aspose.slides/iresourceloadingargs/uri/) | 다운로드에 사용되는 리소스의 URI이며, **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** 가 [`ResourceLoadingAction.DEFAULT`](/slides/python-net/ko/aspose.slides/resourceloadingaction/DEFAULT) 를 반환하는 경우에 사용됩니다. <br/>            처음에는 리소스의 원본 URI로 설정되지만, 임의의 값으로 재정의할 수 있습니다. |

## 메서드

| Method | Description |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/ko/aspose.slides/iresourceloadingargs/set_data/#bytes) | 리소스에 대한 사용자가 제공한 데이터를 설정합니다. 해당 데이터는 **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** 가 [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/ko/aspose.slides/resourceloadingaction/USER_PROVIDED) 를 반환하는 경우에 사용됩니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)