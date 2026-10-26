---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/icommentcollection/insert_comment/
weight: 40
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
새 주석을 지정된 인덱스에 컬렉션에 삽입합니다.

### 반환값
삽입된 주석.

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 컬렉션에서 주석을 삽입해야 하는 요소의 인덱스. |
| text | **str** | 새 주석의 일반 텍스트. |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 새 주석을 추가할 프레젠테이션의 슬라이드. |
| position | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 새 주석을 추가할 슬라이드상의 위치. |
| creation_time | **DateTime** | 주석이 생성된 시간. |

### 참고
* 클래스 [`IComment`](/slides/python-net/ko/aspose.slides/icomment)
* 클래스 [`ICommentCollection`](/slides/python-net/ko/aspose.slides/icommentcollection)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)