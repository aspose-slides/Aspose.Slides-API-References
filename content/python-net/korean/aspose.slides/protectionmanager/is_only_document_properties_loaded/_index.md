---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 속성
이 속성은 프레젠테이션 파일이 비밀번호로 보호되어 있고 해당 파일의 문서 속성이 공개된 경우에 의미가 있습니다.
true 값은 암호화된 프레젠테이션 파일에서 비밀번호 없이 문서 속성만 로드된다는 의미입니다.
false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션이 로드되며, 문서 속성만 로드되는 것이 아니라는 의미입니다.
프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다.
암호화된 파일의 문서 속성이 공개되지 않은 경우 속성 값은 항상 false입니다.
Presentation.EncryptDocumentProperties가 true이면 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다.
읽기 전용 **bool**.

### 정의:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 참조
* class [`ProtectionManager`](/slides/python-net/ko/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)