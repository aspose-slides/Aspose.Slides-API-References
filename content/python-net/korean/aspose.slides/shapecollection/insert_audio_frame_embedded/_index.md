---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python을 통한 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
새로운 오디오 프레임을 만들고, 삽입된 WAV 파일과 함께 지정된 인덱스에 shape 컬렉션에 삽입합니다. 삽입된 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

### 반환

새로 만든 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 삽입할 오디오 프레임의 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x좌표이며, 포인트 단위입니다. |
| y | **float** | 새 오디오 프레임의 y좌표이며, 포인트 단위입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 포인트 단위입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 포인트 단위입니다. |
| audio_stream | **io.RawIOBase** | 삽입할 WAV 오디오 데이터를 포함하는 입력 스트림입니다. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
새로운 오디오 프레임을 만들고, Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환

새로 만든 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 삽입할 오디오 프레임의 0부터 시작하는 인덱스입니다. |
| x | **float** | 새 오디오 프레임의 x좌표이며, 포인트 단위입니다. |
| y | **float** | 새 오디오 프레임의 y좌표이며, 포인트 단위입니다. |
| width | **float** | 새 오디오 프레임의 너비이며, 포인트 단위입니다. |
| height | **float** | 새 오디오 프레임의 높이이며, 포인트 단위입니다. |
| audio | [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 가져온 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) 인스턴스입니다. |



### 참조
* 클래스 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio)
* 클래스 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)