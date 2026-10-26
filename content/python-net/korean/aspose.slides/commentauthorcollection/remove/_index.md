---
title: remove method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/commentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
컬렉션에서 지정된 author의 첫 번째 발생을 제거합니다.


```python
def remove(self, author):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor) | 컬렉션에서 제거할 author. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | author는 `None`입니다 |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | author가 이미 제거된 경우 발생합니다. |



### 참고
* 클래스 [`CommentAuthorCollection`](/slides/python-net/ko/aspose.slides/commentauthorcollection)
* 클래스 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)