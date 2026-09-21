---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
새 오디오 프레임을 생성하고, 삽입된 WAV 파일과 함께 형태 컬렉션의 끝에 추가합니다. 삽입된 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

### 반환
새로 생성된 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio_stream | **io.RawIOBase** | 삽입할 WAV 오디오 데이터를 포함하는 입력 스트림. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
새 오디오 프레임을 생성하고, Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 형태 컬렉션의 끝에 추가합니다.

### 반환
새로 생성된 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio | [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 가져온 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) 인스턴스. |



### 참조
* 클래스 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio)
* 클래스 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)