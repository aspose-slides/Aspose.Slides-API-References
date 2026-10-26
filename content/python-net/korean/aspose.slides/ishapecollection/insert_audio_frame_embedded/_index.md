---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
새로운 오디오 프레임을 생성하고 임베드된 WAV 파일을 포함시켜 지정된 인덱스에 shape 컬렉션에 삽입합니다. 임베드된 오디오는 Presentation.Audios 컬렉션에 추가됩니다.

### 반환값

새로 생성된 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio_stream | **io.RawIOBase** | 임베드할 WAV 오디오 데이터를 포함하는 입력 스트림. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
새로운 오디오 프레임을 생성하고 Presentation.Audios 목록에 있는 기존 오디오 객체를 사용하여 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| audio | [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) | Presentation.Audios 컬렉션에서 임베드할 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio) 인스턴스. |



### 참고
* 클래스 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio)
* 클래스 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)