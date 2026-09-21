---
title: PresentationInfo class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentationinfo/
---
## PresentationInfo 클래스

프레젠테이션 파일에 대한 정보

PresentationInfo 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ko/aspose.slides/presentationinfo/is_encrypted/) | 바인딩된 프레젠테이션이 암호화된 경우 True를 반환하고, 그렇지 않으면 False를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`is_password_protected`](/slides/python-net/ko/aspose.slides/presentationinfo/is_password_protected/) | 바인딩된 프레젠테이션이 열기 비밀번호로 보호되는지 여부를 나타내는 값을 반환합니다. |
| [`is_write_protected`](/slides/python-net/ko/aspose.slides/presentationinfo/is_write_protected/) | 바인딩된 프레젠테이션이 쓰기 보호되는지 여부를 나타내는 값을 반환합니다. |
| [`load_format`](/slides/python-net/ko/aspose.slides/presentationinfo/load_format/) | 바인딩된 프레젠테이션의 형식을 반환합니다.<br/>            읽기 전용 [`LoadFormat`](/slides/python-net/ko/aspose.slides/loadformat). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ko/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | 바인딩된 프레젠테이션을 스트림에 씁니다. |
| [`write_binded_presentation(self, file)`](/slides/python-net/ko/aspose.slides/presentationinfo/write_binded_presentation/#str) | 바인딩된 프레젠테이션을 파일에 씁니다. |
| [`check_password(self, password)`](/slides/python-net/ko/aspose.slides/presentationinfo/check_password/#str) | 열기 비밀번호로 보호된 프레젠테이션에 대해 비밀번호가 올바른지 확인합니다. |
| [`check_write_protection(self, password)`](/slides/python-net/ko/aspose.slides/presentationinfo/check_write_protection/#str) | 쓰기 보호된 프레젠테이션에 대해 수정 비밀번호가 올바른지 확인합니다. |
| [`read_document_properties(self)`](/slides/python-net/ko/aspose.slides/presentationinfo/read_document_properties/#) | 바인딩된 프레젠테이션의 문서 속성을 가져옵니다. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ko/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | 바인딩된 프레젠테이션의 속성을 업데이트합니다. |


### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)