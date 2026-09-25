---
title: IComment class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icomment/
---
## IComment 클래스

슬라이드의 댓글을 나타냅니다.

IComment 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`text`](/slides/python-net/ko/aspose.slides/icomment/text/) | 슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다.<br/>읽기/쓰기 **str**. |
| [`created_time`](/slides/python-net/ko/aspose.slides/icomment/created_time/) | 댓글 생성 시간을 반환하거나 설정합니다.<br/>이 속성을 **System.DateTime**으로 설정하면 댓글 시간이 설정되지 않은 것입니다.<br/>읽기/쓰기 **System.DateTime**. |
| [`slide`](/slides/python-net/ko/aspose.slides/icomment/slide/) | 댓글의 부모 슬라이드를 반환하거나 설정합니다.<br/>읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| [`author`](/slides/python-net/ko/aspose.slides/icomment/author/) | 댓글의 작성자를 반환합니다.<br/>읽기 전용 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ko/aspose.slides/icomment/position/) | 슬라이드에서 댓글의 위치를 반환하거나 설정합니다.<br/>읽기/쓰기 [`PointF`](/slides/python-net/ko/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/ko/aspose.slides/icomment/parent_comment/) | 부모 댓글을 가져오거나 설정합니다.<br/>읽기/쓰기 [`IComment`](/slides/python-net/ko/aspose.slides/icomment). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/icomment/remove/#) | 댓글 및 해당 댓글의 모든 답글을 부모 컬렉션에서 제거합니다. |

### 관련 항목
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)