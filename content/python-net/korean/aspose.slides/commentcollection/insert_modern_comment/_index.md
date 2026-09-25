---
title: insert_modern_comment method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/commentcollection/insert_modern_comment/
weight: 60
---
## insert_modern_comment(self, index, text, slide, shape, position, creation_time) {#int-str-islide-ishape-asposeslidespointf-datetime}
지정된 인덱스에 새로운 현대 댓글을 컬렉션에 삽입합니다.

### 반환값

삽입된 현대 댓글.

```python
def insert_modern_comment(self, index, text, slide, shape, position, creation_time):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 컬렉션에서 현대 댓글을 삽입해야 하는 요소의 인덱스입니다. |
| text | **str** | 새로운 현대 댓글의 순수 텍스트입니다. |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 새로운 현대 댓글을 추가할 프레젠테이션의 슬라이드입니다. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 새로운 현대 댓글이 연결되는 슬라이드의 도형입니다. |
| position | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 새로운 현대 댓글을 추가할 슬라이드의 위치입니다. |
| creation_time | **DateTime** | 현대 댓글이 생성된 시간입니다. |

### 참고
* 클래스 [`CommentCollection`](/slides/python-net/ko/aspose.slides/commentcollection)
* 클래스 [`IModernComment`](/slides/python-net/ko/aspose.slides/imoderncomment)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)