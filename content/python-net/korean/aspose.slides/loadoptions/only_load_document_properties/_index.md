---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties 속성
프레젠테이션 파일이 비밀번호로 보호된 경우 이 속성은 의미가 있습니다.
true 값을 지정하면 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시해야 함을 의미합니다.
false 값을 지정하면 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드해야 함을 의미합니다.
프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 무시됩니다.
암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다.
읽기/쓰기 **bool**.

### 정의:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### 참조
* 클래스 [`LoadOptions`](/slides/python-net/ko/aspose.slides/loadoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)