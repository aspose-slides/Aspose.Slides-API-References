---
title: check_password method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
열린 비밀번호로 보호된 프레젠테이션에 대해 비밀번호가 올바른지 확인합니다.

### 반환값

프레젠테이션이 열린 비밀번호로 보호되어 있고 비밀번호가 올바른 경우 True 를 반환하고, 그렇지 않으면 false 를 반환합니다.



```python
def check_password(self, password):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| password | **str** | 확인할 비밀번호입니다. |

### 비고

비밀번호가 None 이거나 비어 있는 경우, 이 메서드는 false 를 반환합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### 참조
* 클래스 [`PresentationInfo`](/slides/python-net/ko/aspose.slides/presentationinfo)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)