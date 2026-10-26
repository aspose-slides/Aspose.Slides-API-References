---
title: group method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathdelimiter/group/
weight: 90
---
## group(self) {#}
이 요소를 아래 중괄호를 사용하여 그룹에 배치합니다

### Returns

새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
그룹 문자(예: 아래 중괄호 등)를 사용하여 이 요소를 그룹에 배치합니다

### Returns

새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| character | **char** | 그룹 문자 예: 아래 중괄호 (U+23DF) 또는 기타 |
| position | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹 문자의 위치 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹 문자의 수직 정렬.<br/><br/>            객체가 기준선에 대해 어떻게 정렬되는지 지정합니다.<br/><br/>            예를 들어, 그룹 문자가 객체 위에 있을 때,<br/><br/>            Top의 VerticalJustification은 객체의 상단이 기준선에 놓인다는 의미입니다;<br/><br/>            VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 놓입니다 |



### 관련 항목
* 클래스 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)
* 클래스 [`MathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter)
* 열거형 [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)