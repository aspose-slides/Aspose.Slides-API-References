---
title: insert_audio_frame_linked method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_audio_frame_linked/
weight: 220
---
## insert_audio_frame_linked(self, index, x, y, width, height, fname) {#int-float-float-float-float-str}
외부 오디오 파일에 연결된 새 오디오 프레임을 생성하고 지정된 인덱스에 있는 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe).



```python
def insert_audio_frame_linked(self, index, x, y, width, height, fname):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 오디오 프레임을 삽입할 0부터 시작하는 인덱스. |
| x | **float** | 새 오디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 오디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 오디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 오디오 프레임의 높이(포인트 단위). |
| fname | **str** | 연결할 외부 오디오 파일의 경로나 이름. |



### 참고
* 클래스 [`IAudioFrame`](/slides/python-net/ko/aspose.slides/iaudioframe)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)