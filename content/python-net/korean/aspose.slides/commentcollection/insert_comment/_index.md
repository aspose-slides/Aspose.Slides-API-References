---
title: insert_comment method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/commentcollection/insert_comment/
weight: 50
---
## insert_comment(self, index, text, slide, position, creation_time) {#int-str-islide-asposepydrawingpointf-datetime}
지정된 인덱스에 컬렉션에 새 댓글을 삽입합니다.

### 반환

삽입된 댓글.



```python
def insert_comment(self, index, text, slide, position, creation_time):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 댓글을 삽입해야 하는 컬렉션 내 요소의 인덱스입니다. |
| text | **str** | 새 댓글의 일반 텍스트입니다. |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 새 댓글을 추가할 프레젠테이션의 슬라이드입니다. |
| position | **aspose.slides.PointF** | 새 댓글을 추가할 슬라이드상의 위치입니다. |
| creation_time | **DateTime** | 댓글이 생성된 시간입니다. |



### 참고
* 클래스 [`CommentCollection`](/slides/python-net/ko/aspose.slides/commentcollection)
* 클래스 [`IComment`](/slides/python-net/ko/aspose.slides/icomment)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)