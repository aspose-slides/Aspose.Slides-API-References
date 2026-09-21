---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
프레젠테이션이 수정에 대한 비밀번호 보호가 되어 있는지 여부를 판단합니다.

### 반환값

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | **str** | 확인할 password. |

### 비고

1. 이 메서드를 호출하기 전에 [`ProtectionManager.is_write_protected`](/slides/python-net/ko/aspose.slides/protectionmanager/is_write_protected) 속성을 확인해야 합니다.
2. password가 None이거나 비어 있을 때, 이 메서드는 false를 반환합니다.



### 관련 항목
* 클래스 [`ProtectionManager`](/slides/python-net/ko/aspose.slides/protectionmanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)