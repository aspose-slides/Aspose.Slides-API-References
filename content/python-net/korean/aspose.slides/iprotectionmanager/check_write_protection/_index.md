---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
프레젠테이션이 수정에 대한 비밀번호 보호가 되었는지 여부를 판단합니다.

### 반환값

비밀번호가 유효하면 True, 그렇지 않으면 false.

```python
def check_write_protection(self, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | **str** | 확인할 비밀번호. |

### 비고

1. 이 메서드를 호출하기 전에 [`IProtectionManager.is_write_protected`](/slides/python-net/ko/aspose.slides/iprotectionmanager/is_write_protected) 속성을 확인해야 합니다.
2. 비밀번호가 None이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.

### 참조
* 클래스 [`IProtectionManager`](/slides/python-net/ko/aspose.slides/iprotectionmanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)