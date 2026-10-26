---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
수학 요소를 괄호로 감쌉니다

### 반환값

type [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)인 수학 요소이며 괄호를 포함합니다



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화합니다

### 반환값

type [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)인 수학 요소이며 지정된 문자를 프레임으로 포함합니다



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| beginning_character | **char** | 시작 문자 (보통 왼쪽 괄호) |
| ending_character | **char** | 끝 문자 (보통 오른쪽 괄호) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임화하고 구분 문자로 구분합니다

### 반환값

type [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)인 수학 요소이며 지정된 문자를 프레임 및 구분자로 포함합니다



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| beginning_character | **char** | 시작 문자 (보통 왼쪽 괄호) |
| ending_character | **char** | 끝 문자 (보통 오른쪽 괄호) |
| separator_character | **char** | 구분 문자 |



### 참조
* 클래스 [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)
* 클래스 [`MathBlock`](/slides/python-net/ko/aspose.slides.mathtext/mathblock)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)