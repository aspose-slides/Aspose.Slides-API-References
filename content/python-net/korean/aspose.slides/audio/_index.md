---
title: Audio class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/audio/
---
## Audio 클래스

임베디드 오디오 파일을 나타냅니다.

Audio 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`content_type`](/slides/python-net/ko/aspose.slides/audio/content_type/) | 오디오의 MIME 타입을 반환하며, [`Audio.binary_data`](/slides/python-net/ko/aspose.slides/audio/binary_data)로 인코딩됩니다.<br/>            읽기 전용 **str**. |
| [`binary_data`](/slides/python-net/ko/aspose.slides/audio/binary_data/) | 오디오 데이터의 복사본을 반환합니다. 대량의 데이터를 처리하는 경우 <br/>            [`Audio.get_stream`](/slides/python-net/ko/aspose.slides/audio/get_stream) 메서드를 사용하여 오디오 데이터의 불필요한 메모리 로드 또는 OutOfMemoryException 발생을 방지하는 것을 고려하십시오.<br/>            읽기 전용 **int**[]. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ko/aspose.slides/audio/get_stream/#) | 읽기를 위한 Stream 스트림을 반환합니다.<br/>            'using'을 사용하거나 사용 후 스트림을 닫으십시오. |


### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)