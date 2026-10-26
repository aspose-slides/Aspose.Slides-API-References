---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
수정용 비밀번호가 쓰기 보호된 프레젠테이션에 대해 올바른지 확인합니다.

### Returns

프레젠테이션이 쓰기 보호되어 있고 비밀번호가 올바른 경우 true를 반환합니다. 그렇지 않으면 false를 반환합니다.



```python
def check_write_protection(self, password):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | **str** | 확인할 비밀번호입니다. |

### Remarks

1. 이 메서드를 호출하기 전에 [`IPresentationInfo.is_write_protected`](/slides/python-net/ko/aspose.slides/ipresentationinfo/is_write_protected) 속성을 확인해야 합니다.
            2. password가 None이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.

### Exceptions

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### See Also
* 클래스 [`IPresentationInfo`](/slides/python-net/ko/aspose.slides/ipresentationinfo)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)