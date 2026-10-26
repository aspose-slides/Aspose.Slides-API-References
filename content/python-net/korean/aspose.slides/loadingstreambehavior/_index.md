---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 열거형

**io.RawIOBase**가 메서드에 전달될 때 이 객체는 바이너리 대용량 객체(BLOB)로 간주됩니다([`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions) 설명 참조). 이 열거형의 값은 **io.RawIOBase**가 메서드에 전달될 때 어떻게 처리되어야 하는지를 나타냅니다. 요구 사항에 따라 가장 효율적인 동작을 제공하기 위한 다양한 결정이 이루어질 수 있습니다.

LoadingStreamBehavior 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| READ_STREAM_AND_RELEASE | 스트림이 끝까지 읽힌 후 해제됩니다. 즉, 앞으로 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스에서 이 스트림이 사용되지 않을 것이 보장됩니다. 클라이언트 코드에서 스트림을 닫거나 다른 방식으로 사용할 수 있습니다. |
| KEEP_LOCKED | 스트림이 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 객체 내에 잠겨 있으며, 스트림의 소유권이 이전됩니다. [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 객체는 이 객체가 자체적으로 해제될 때 스트림을 올바르게 해제할 책임이 있습니다. 이 동작은 큰 BLOB 파일(예: 큰 비디오 또는 오디오 - [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions) 설명 참조)을 직렬화해야 하고 이 파일을 메모리로 로드하거나 기타 성능 문제를 방지하려는 경우에 매우 유용합니다. 해당 파일에 대해 **System.IO.FileStream**을 열고 메서드에 전달하면서 [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/ko/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior를 선택하면 됩니다. |

### 참조
* 클래스 [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)