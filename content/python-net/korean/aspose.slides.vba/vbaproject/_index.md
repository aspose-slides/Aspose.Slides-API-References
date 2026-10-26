---
title: VbaProject class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.vba/vbaproject/
---
## VbaProject 클래스

프레젠테이션 매크로가 포함된 VBA 프로젝트를 나타냅니다.

VbaProject 타입은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.vba/vbaproject/__init__/#) | 이 생성자는 새 VBA 프로젝트를 처음부터 생성합니다.<br/>            프로젝트는 1252 Windows Latin 1 (ANSI) 코드 페이지에서 생성됩니다 |
| [`__init__(self, data)`](/slides/python-net/ko/aspose.slides.vba/vbaproject/__init__/#bytes) | 이 생성자는 OLE 컨테이너의 바이너리 표현에서 VBA 프로젝트를 로드합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`name`](/slides/python-net/ko/aspose.slides.vba/vbaproject/name/) | VBA 프로젝트의 이름을 반환합니다.<br/>            읽기 전용 **str**. |
| [`modules`](/slides/python-net/ko/aspose.slides.vba/vbaproject/modules/) | VBA 프로젝트에 포함된 모든 모듈의 목록을 반환합니다.<br/>            읽기 전용 [`IVbaModuleCollection`](/slides/python-net/ko/aspose.slides.vba/ivbamodulecollection). |
| [`references`](/slides/python-net/ko/aspose.slides.vba/vbaproject/references/) | VBA 프로젝트에 포함된 모든 참조의 목록을 반환합니다.<br/>            읽기 전용 [`IVbaReferenceCollection`](/slides/python-net/ko/aspose.slides.vba/ivbareferencecollection). |
| [`is_password_protected`](/slides/python-net/ko/aspose.slides.vba/vbaproject/is_password_protected/) | VBAProject가 프로젝트 속성을 보기 위해 비밀번호로 보호되는지 여부를 나타냅니다.<br/>            읽기 전용 **bool**. |

## 메서드

| Method | Description |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/ko/aspose.slides.vba/vbaproject/to_binary/#) | VBA 프로젝트를 OLE 컨테이너 형식의 바이너리 표현으로 반환합니다 |

### 참고
* 모듈 [`aspose.slides.vba`](/slides/python-net/ko/aspose.slides.vba)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)