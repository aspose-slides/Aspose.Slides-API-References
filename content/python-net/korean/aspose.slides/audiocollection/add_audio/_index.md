---
title: add_audio method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
다른 프레젠테이션에서 오디오 파일의 복사본을 추가합니다.

### 반환값

추가된 오디오.

```python
def add_audio(self, audio):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) | 소스 오디오. |

## add_audio(self, stream) {#iorawiobase}
스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

### 반환값

추가된 오디오.

```python
def add_audio(self, stream):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 오디오를 추가할 스트림. |

## add_audio(self, audio_data) {#bytes}
바이트 배열에서 오디오를 생성하고 프레젠테이션에 추가합니다.

### 반환값

추가된 오디오.

```python
def add_audio(self, audio_data):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| audio_data | **bytes** | 오디오 바이트. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
스트림에서 오디오를 생성하고 프레젠테이션에 추가합니다.

### 반환값

추가된 오디오.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 비디오 오디오를 추가할 스트림. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior) | 스트림에 적용될 동작. |

### 참고
* 클래스 [`AudioCollection`](/slides/python-net/ko/aspose.slides/audiocollection)
* 클래스 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio)
* 열거형 [`LoadingStreamBehavior`](/slides/python-net/ko/aspose.slides/loadingstreambehavior)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)