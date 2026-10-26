---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
지정된 사전 정의된 색상으로부터 색상을 생성합니다.<br/>이것은 시스템 색상(예: `KnownColor.CONTROL`)을 얻는 유일한 방법입니다: 시스템 색상은 `Color` 속성으로 노출되지 않으며, 그 값은 데스크톱 테마에 따라 달라지므로 라이브러리 런타임에서 읽어옵니다.

### 반환값

이 메서드가 생성하는 색상입니다.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| known_color | **KnownColor** | `KnownColor` 열거형의 요소(`IntEnum`으로 .NET `System.Drawing.KnownColor`를 반영) 또는 해당 정수 값입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 해당 값이 유효한 `KnownColor` 멤버가 아닙니다. |



### 참고
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)