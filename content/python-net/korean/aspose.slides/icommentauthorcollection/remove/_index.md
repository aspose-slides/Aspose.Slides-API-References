---
title: remove method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentauthorcollection/remove/
weight: 50
---
## remove(self, author) {#icommentauthor}
지정된 작성자를 컬렉션에서 첫 번째로 나타나는 항목을 제거합니다.

```python
def remove(self, author):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| author | [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor) | 컬렉션에서 제거할 작성자. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 작성자가 `None`인 경우 |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 작성자가 이미 제거된 경우 발생합니다. |

### 참조
* 클래스 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor)
* 클래스 [`ICommentAuthorCollection`](/slides/python-net/ko/aspose.slides/icommentauthorcollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)