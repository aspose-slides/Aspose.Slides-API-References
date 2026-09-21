---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
쓰기 보호된 프레젠테이션에 대해 수정 비밀번호가 올바른지 확인합니다.

### 반환값

True if the presentation is write protected and the password is correct. False otherwise.



```python
def check_write_protection(self, password):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | **str** | The password to check. |

### 비고

1. 이 메서드를 호출하기 전에 [`PresentationInfo.is_write_protected`](/slides/python-net/ko/aspose.slides/presentationinfo/is_write_protected) 속성을 확인해야 합니다.
2. password가 None이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### 참조
* 클래스 [`PresentationInfo`](/slides/python-net/ko/aspose.slides/presentationinfo)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)