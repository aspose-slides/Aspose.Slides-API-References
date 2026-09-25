---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposeslidespointf-datetime}
컬렉션의 지정된 인덱스에 새 댓글을 삽입합니다.

### 반환
삽입된 코멘트.

```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 컬렉션에서 댓글을 삽입해야 하는 요소의 인덱스. |
| text | **str** | 새 댓글의 일반 텍스트. |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드. |
| position | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 새 댓글을 추가할 슬라이드의 위치. |
| creation_time | **DateTime** | 댓글 생성 시간. |

### 참조
* 클래스 [`CommentCollection`](/slides/python-net/ko/aspose.slides/commentcollection)
* 클래스 [`IComment`](/slides/python-net/ko/aspose.slides/icomment)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)