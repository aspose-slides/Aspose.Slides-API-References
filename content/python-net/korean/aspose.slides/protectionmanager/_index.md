---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/protectionmanager/
---
## ProtectionManager 클래스

프레젠테이션 비밀번호 보호 관리.

ProtectionManager 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/ko/aspose.slides/protectionmanager/encrypt_document_properties/) | 프레젠테이션이 비밀번호로 보호되는 경우에만 이 속성이 의미가 있습니다.<br/>            true인 경우 문서 속성이 프레젠테이션 파일에서 암호화됩니다.<br/>            false인 경우 문서 속성이 공개되지만 프레젠테이션은 암호화됩니다.<br/>            읽기/쓰기 **bool**. |
| [`is_encrypted`](/slides/python-net/ko/aspose.slides/protectionmanager/is_encrypted/) | 이 인스턴스가 암호화되었는지 여부를 나타내는 값을 가져옵니다.<br/>            읽기 전용 **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/ko/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | 프레젠테이션 파일이 비밀번호로 보호되고 해당 파일의 문서 속성이 공개된 경우에만 이 속성이 의미가 있습니다.<br/>            true 값은 비밀번호 없이 암호화된 프레젠테이션 파일에서 문서 속성만 로드된다는 뜻입니다.<br/>            false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드한다는 뜻이며, 문서 속성만 로드되는 것이 아닙니다.<br/>            프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 false입니다.<br/>            암호화된 파일의 문서 속성이 공개되지 않은 경우 속성 값은 항상 false입니다.<br/>            Presentation.EncryptDocumentProperties가 true인 경우 IsOnlyDocumentPropertiesLoaded 속성 값은 항상 false입니다.<br/>            읽기 전용 **bool**. |
| [`is_write_protected`](/slides/python-net/ko/aspose.slides/protectionmanager/is_write_protected/) | 이 프레젠테이션이 쓰기 보호되어 있는지 여부를 나타내는 값을 가져옵니다.<br/>            읽기 전용 **bool**. |
| [`encryption_password`](/slides/python-net/ko/aspose.slides/protectionmanager/encryption_password/) | 프레젠테이션 암호화에 사용되는 비밀번호를 가져옵니다.<br/>            읽기 전용 **str**. |
| [`read_only_recommended`](/slides/python-net/ko/aspose.slides/protectionmanager/read_only_recommended/) | 읽기 전용 권장 설정을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/ko/aspose.slides/protectionmanager/encrypt/#str) | 지정된 비밀번호로 프레젠테이션을 암호화합니다. |
| [`remove_encryption(self)`](/slides/python-net/ko/aspose.slides/protectionmanager/remove_encryption/#) | 암호화를 제거합니다. |
| [`set_write_protection(self, password)`](/slides/python-net/ko/aspose.slides/protectionmanager/set_write_protection/#str) | 지정된 비밀번호로 이 프레젠테이션에 쓰기 보호를 설정합니다. |
| [`remove_write_protection(self)`](/slides/python-net/ko/aspose.slides/protectionmanager/remove_write_protection/#) | 이 프레젠테이션의 쓰기 보호를 제거합니다. |
| [`check_write_protection(self, password)`](/slides/python-net/ko/aspose.slides/protectionmanager/check_write_protection/#str) | 프레젠테이션이 수정할 때 비밀번호로 보호되는지 여부를 판단합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)