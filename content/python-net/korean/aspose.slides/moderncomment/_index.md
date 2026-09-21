---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/moderncomment/
---
## ModernComment 클래스

슬라이드에 대한 댓글을 나타냅니다.

**상속:**[`ModernComment`](/slides/python-net/ko/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/ko/aspose.slides/comment)

ModernComment 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`text`](/slides/python-net/ko/aspose.slides/moderncomment/text/) | 슬라이드 댓글의 일반 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`created_time`](/slides/python-net/ko/aspose.slides/moderncomment/created_time/) | 댓글 생성 시간을 반환하거나 설정합니다.<br/>            이 속성을 **System.DateTime** 로 설정하면 댓글 시간이 설정되지 않은 것입니다.<br/>            읽기/쓰기 **System.DateTime**. |
| [`slide`](/slides/python-net/ko/aspose.slides/moderncomment/slide/) | 댓글의 상위 슬라이드를 반환하거나 설정합니다.<br/>            읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| [`author`](/slides/python-net/ko/aspose.slides/moderncomment/author/) | 댓글의 작성자를 반환합니다.<br/>            읽기 전용 [`ICommentAuthor`](/slides/python-net/ko/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/ko/aspose.slides/moderncomment/position/) | 슬라이드에서 댓글의 위치를 반환하거나 설정합니다.<br/>            읽기/쓰기 **aspose.slides.PointF**. |
| [`parent_comment`](/slides/python-net/ko/aspose.slides/moderncomment/parent_comment/) | 상위 댓글을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IComment`](/slides/python-net/ko/aspose.slides/icomment). |
| [`shape`](/slides/python-net/ko/aspose.slides/moderncomment/shape/) | 댓글과 연결된 도형을 반환합니다.<br/>            읽기 전용 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/ko/aspose.slides/moderncomment/text_selection_start/) | 댓글이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 시작 위치를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`text_selection_length`](/slides/python-net/ko/aspose.slides/moderncomment/text_selection_length/) | 댓글이 AutoShape와 연결된 경우 텍스트 프레임에서 텍스트 선택 길이를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`status`](/slides/python-net/ko/aspose.slides/moderncomment/status/) | 댓글의 상태를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`ModernCommentStatus`](/slides/python-net/ko/aspose.slides/moderncommentstatus). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides/moderncomment/remove/#) | 부모 컬렉션에서 댓글과 모든 답글을 제거합니다. |

### 참조
* 클래스 [`Comment`](/slides/python-net/ko/aspose.slides/comment)
* 클래스 [`ModernComment`](/slides/python-net/ko/aspose.slides/moderncomment)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)