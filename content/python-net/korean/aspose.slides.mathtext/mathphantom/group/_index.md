---
title: group method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathphantom/group/
weight: 80
---
## group(self) {#}
이 요소를 하단 중괄호를 사용하여 그룹에 배치합니다

### 반환값

새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
이 요소를 하단 중괄호와 같은 그룹화 문자 또는 다른 문자를 사용하여 그룹에 배치합니다

### 반환값

새 인스턴스 유형 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| character | **char** | BOTTOM CURLY BRACKET (U+23DF)와 같은 그룹화 문자 또는 기타 문자 |
| position | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹화 문자 위치 |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions) | 그룹 문자에 대한 수직 정렬.<br/><br/>            객체를 기준선에 대해 정렬하는 방식을 지정합니다.<br/><br/>            예를 들어, 그룹 문자가 객체 위에 있을 때,<br/><br/>            VerticalJustification이 Top이면 객체의 상단이 기준선에 맞춰짐을 의미합니다;<br/><br/>            VerticalJustification이 Bottom으로 설정되면 객체의 하단이 기준선에 맞춰집니다 |



### 참고
* 클래스 [`IMathGroupingCharacter`](/slides/python-net/ko/aspose.slides.mathtext/imathgroupingcharacter)
* 클래스 [`MathPhantom`](/slides/python-net/ko/aspose.slides.mathtext/mathphantom)
* 열거형 [`MathTopBotPositions`](/slides/python-net/ko/aspose.slides.mathtext/mathtopbotpositions)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)