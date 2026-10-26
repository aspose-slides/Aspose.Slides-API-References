---
title: IVideo class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ivideo/
---
## IVideo 클래스

프레젠테이션에 삽입된 비디오를 나타냅니다.

IVideo 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`content_type`](/slides/python-net/ko/aspose.slides/ivideo/content_type/) | 비디오의 MIME 타입을 반환합니다. [`IVideo.binary_data`](/slides/python-net/ko/aspose.slides/ivideo/binary_data)에 인코딩됩니다.<br/>            읽기 전용 **str**. |
| [`binary_data`](/slides/python-net/ko/aspose.slides/ivideo/binary_data/) | 오디오 데이터의 복사본을 반환합니다. 대량의 데이터를 다룰 경우 <br/>            [`IVideo.get_stream`](/slides/python-net/ko/aspose.slides/ivideo/get_stream) 메서드를 사용하여 비디오 데이터가 메모리에 불필요하게 로드되는 것을 방지하거나 <br/>            OutOfMemoryException이 발생하는 것을 방지하십시오.<br/>            읽기 전용 **int**[]. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ko/aspose.slides/ivideo/get_stream/#) | 읽기를 위한 Stream 스트림을 반환합니다.<br/>            사용 후 'using'을 사용하거나 스트림을 닫으세요. |


### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)