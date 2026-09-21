---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentcollection/insert_modern_comment/
weight: 50
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposepydrawingpointf-datetime}
지정된 인덱스에서 컬렉션에 새로운 최신 주석을 삽입합니다.

### 반환
삽입된 최신 주석.

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 컬렉션에서 최신 주석을 삽입해야 하는 요소의 인덱스. |
| text | **str** | 새로운 최신 주석의 일반 텍스트. |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 프레젠테이션에서 새로운 최신 주석을 추가할 슬라이드. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 새로운 최신 주석이 연결되는 슬라이드의 도형. |
| position | **aspose.slides.PointF** | 새로운 최신 주석을 추가할 슬라이드상의 위치. |
| creation_time | **DateTime** | 최신 주석이 생성된 시간. |

### 참고
* 클래스 [`ICommentCollection`](/slides/python-net/ko/aspose.slides/icommentcollection)
* 클래스 [`IModernComment`](/slides/python-net/ko/aspose.slides/imoderncomment)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)