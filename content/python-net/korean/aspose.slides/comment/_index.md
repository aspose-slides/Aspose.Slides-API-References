---
title: Comment class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/comment/
---
## Comment 클래스

슬라이드에 대한 주석을 나타냅니다.

Comment 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/ko/aspose.slides/comment/text/) | 슬라이드 주석의 일반 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`created_time`](/slides/python-net/ko/aspose.slides/comment/created_time/) | 주석 생성 시간을 반환하거나 설정합니다.<br/>            이 속성을 **System.DateTime** 로 설정하면 주석 시간이 설정되지 않은 것입니다.<br/>            읽기/쓰기 **System.DateTime**. |
| [`slide`](/slides/python-net/ko/aspose.slides/comment/slide/) | 주석의 상위 슬라이드를 반환하거나 설정합니다.<br/>            읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| [`author`](/slides/python-net/ko/aspose.slides/comment/author/) | 주석의 작성자를 반환합니다.<br/>            읽기 전용 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ko/aspose.slides/comment/position/) | 슬라이드에서 주석의 위치를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`PointF`](/slides/python-net/ko/aspose.slides/pointf). |
| [`parent_comment`](/slides/python-net/ko/aspose.slides/comment/parent_comment/) | 상위 주석을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`IComment`](/slides/python-net/ko/aspose.slides/icomment). |

## 메서드

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/comment/remove/#) | 주석 및 해당 모든 답글을 상위 컬렉션에서 제거합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)