---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 속성
프레젠테이션 파일이 암호로 보호되고 이 파일의 문서 속성이 공개된 경우 이 속성은 의미가 있습니다.
true 값은 암호를 사용하지 않고 암호화된 프레젠테이션 파일에서 문서 속성만 로드된다는 의미입니다.
false 값은 올바른 암호를 사용하여 전체 암호화된 프레젠테이션이 로드되며, 문서 속성만 로드되는 것이 아니라는 의미입니다.
프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다.
암호화된 파일의 문서 속성이 공개되지 않은 경우 속성 값은 항상 false입니다.
PresentationEx.EncryptDocumentProperties가 true인 경우 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다.
읽기 전용 **bool**.

### 정의:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 참고
* 클래스 [`IProtectionManager`](/slides/python-net/ko/aspose.slides/iprotectionmanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)