---
title: add_author method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/icommentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
컬렉션의 끝에 새 저자를 추가합니다.

### Returns

새로운 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor) 객체.

```python
def add_author(self, name, initials):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | **str** | 새 저자의 이름. |
| initials | **str** | 새 저자의 이니셜. |

### Exceptions

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 같은 이름과 이니셜을 가진 저자가 이미 추가된 경우 발생합니다. |

### 참고
* 클래스 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor)
* 클래스 [`ICommentAuthorCollection`](/slides/python-net/ko/aspose.slides/icommentauthorcollection)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)