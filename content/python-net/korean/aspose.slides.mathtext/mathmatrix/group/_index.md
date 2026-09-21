---
title: group method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다

### Returns
새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
이 요소를 그룹화 문자(예: 하단 중괄호 등)를 사용하여 그룹에 배치합니다

### Returns
새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF)와 같은 그룹화 문자 또는 기타 문자 |
| position | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹화 문자의 위치 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹 문자에 대한 수직 정렬.<br/><br/>            객체가 기준선에 대해 어떻게 정렬되는지 지정합니다.<br/><br/>            예를 들어, 그룹 문자가 객체 위에 있을 때,<br/><br/>            Top의 VerticalJustification은 객체의 상단이 기준선에 위치함을 의미합니다;<br/><br/>            VerticalJustification이 Bottom으로 설정되면, 객체의 하단이 기준선에 위치합니다 |



### See Also
* 클래스 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)
* 클래스 [`MathMatrix`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix)
* 열거형 [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)