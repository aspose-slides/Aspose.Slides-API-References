---
title: add_video method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
다른 프레젠테이션에서 비디오 파일의 복사본을 추가합니다.

### 반환

추가된 비디오.

```python
def add_video(self, video):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo) | 소스 비디오. |

## add_video(self, video_data) {#bytes}
바이트 배열에서 프레젠테이션에 비디오를 생성하고 추가합니다.

### 반환

추가된 비디오.

```python
def add_video(self, video_data):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| video_data | **bytes** | 비디오 바이트. |

## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
스트림에서 프레젠테이션에 비디오를 생성하고 추가합니다.

### 반환

추가된 [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo).

```python
def add_video(self, stream, loading_stream_behavior):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 비디오 파일을 추가할 스트림. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior) | 스트림에 적용될 동작. |

### 참고
* 클래스 [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo)
* 클래스 [`IVideoCollection`](/slides/python-net/ko/aspose.slides/ivideocollection)
* 열거형 [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)