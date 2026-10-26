---
title: add_author method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/commentauthorcollection/add_author/
weight: 10
---
## add_author(self, name, initials) {#str-str}
컬렉션의 끝에 새 저자를 추가합니다.

### 반환값

새 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor) 객체.

```python
def add_author(self, name, initials):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| name | **str** | 새 저자의 이름. |
| initials | **str** | 새 저자의 이니셜. |

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 동일한 이름과 이니셜을 가진 저자가 이미 추가된 경우 발생합니다. |

### 참조
* 클래스 [`CommentAuthorCollection`](/slides/python-net/ko/aspose.slides/commentauthorcollection)
* 클래스 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)