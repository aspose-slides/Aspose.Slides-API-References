---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
새 비디오 프레임을 생성하고 shape 컬렉션 끝에 추가합니다.

### 반환값
새로 생성된 [`IVideoFrame`](/slides/python-net/ko/aspose.slides/ivideoframe).

```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 비디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 비디오 프레임의 높이(포인트 단위). |
| fname | **str** | 삽입할 비디오 파일의 경로 또는 이름. |

## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
새 비디오 프레임을 생성하고 shape 컬렉션 끝에 추가합니다.

### 반환값
새로 생성된 [`IVideoFrame`](/slides/python-net/ko/aspose.slides/ivideoframe).

```python
def add_video_frame(self, x, y, width, height, video):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 새 비디오 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 비디오 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 비디오 프레임의 너비(포인트 단위). |
| height | **float** | 새 비디오 프레임의 높이(포인트 단위). |
| video | [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo) | 비디오 프레임에 삽입할 [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo). |

### 참조
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 클래스 [`IVideo`](/slides/python-net/ko/aspose.slides/ivideo)
* 클래스 [`IVideoFrame`](/slides/python-net/ko/aspose.slides/ivideoframe)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)