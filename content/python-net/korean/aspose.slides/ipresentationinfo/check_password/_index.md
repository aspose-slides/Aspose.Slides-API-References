---
title: check_password method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ipresentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
프레젠테이션이 오픈 비밀번호로 보호된 경우, 비밀번호가 올바른지 확인합니다.

### 반환값

True if the presentation is protected with open password and the password is correct and false otherwise.

```python
def check_password(self, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | **str** | 확인할 비밀번호. |

### 비고

비밀번호가 None이거나 비어 있는 경우, 이 메서드는 false를 반환합니다.

### 참고
* 클래스 [`IPresentationInfo`](/slides/python-net/ko/aspose.slides/ipresentationinfo)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)