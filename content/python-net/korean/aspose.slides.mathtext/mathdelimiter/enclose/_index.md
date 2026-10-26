---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
수학 요소를 괄호로 둘러쌉니다

### 반환

[`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter) 유형의 수학 요소로 괄호를 포함합니다



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
수학 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레이밍합니다

### 반환

만약 `beginning_character`와 `ending_character`가 None이면, 해당 속성에 값만 할당되고 새 객체가 생성되지 않습니다(이 인스턴스를 반환합니다). 그렇지 않으면, 지정된 문자를 프레이밍으로 포함하는 Delimiter 유형의 새로운 수학 요소를 반환하고 [`MathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter) 인스턴스를 그 안에 프레임합니다.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| beginning_character | **char** | 시작 문자 (보통 왼쪽 괄호) |
| ending_character | **char** | 끝 문자 (보통 오른쪽 괄호) |



### 참조
* 클래스 [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)
* 클래스 [`MathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/mathdelimiter)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)