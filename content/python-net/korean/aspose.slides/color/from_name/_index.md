---
title: from_name method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
지정된 미리 정의된 색상의 이름으로 색상을 생성합니다.<br/>검색은 대소문자를 구분하지 않으며 밑줄과 공백을 무시합니다: `"LightBlue"`, `"lightblue"` 및 `"light_blue"`는 모두 `Color.light_blue`로 해석됩니다. [`Color`](/slides/python-net/ko/aspose.slides/color) 클래스 페이지에서 미리 정의된 색상의 목록을 확인하세요.

### 반환값

지정된 색상.



```python
@staticmethod
def from_name(name):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | **str** | 미리 정의된 색상의 이름인 문자열입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 해당 이름은 미리 정의된 색상의 이름이 아닙니다. |
| **TypeError** | 해당 이름은 문자열이 아닙니다. |



### 참고
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)