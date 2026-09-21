---
title: ICommentCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icommentcollection/
---
## ICommentCollection 클래스

하나의 작성자에 대한 주석 컬렉션을 나타냅니다.

ICommentCollection 타입은 다음 멤버를 노출합니다:

지정된 인덱스에 있는 요소를 가져옵니다.
            읽기 전용 [`IComment`](/slides/python-net/ko/aspose.slides/icomment).

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides/icommentcollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`to_array(self)`](/slides/python-net/ko/aspose.slides/icommentcollection/to_array/#) | 모든 주석을 포함하는 배열을 만들고 반환합니다. |
| [`to_array(self, start_index, count)`](/slides/python-net/ko/aspose.slides/icommentcollection/to_array/#int-int) | 지정된 범위의 모든 주석을 포함하는 배열을 만들고 반환합니다. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/ko/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | 컬렉션 끝에 새 주석을 추가합니다. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/ko/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | 컬렉션 끝에 새 현대 주석을 추가합니다. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/ko/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | 지정된 인덱스에 새 주석을 컬렉션에 삽입합니다. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/ko/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | 지정된 인덱스에 새 현대 주석을 컬렉션에 삽입합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/icommentcollection/remove_at/#int) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |
| [`remove(self, comment)`](/slides/python-net/ko/aspose.slides/icommentcollection/remove/#icomment) | 컬렉션에서 지정된 주석의 첫 번째 발생을 제거합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides/icommentcollection/clear/#) | 컬렉션에서 모든 주석을 제거합니다. |

### 참고
* 클래스 [`IComment`](/slides/python-net/ko/aspose.slides/icomment)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)