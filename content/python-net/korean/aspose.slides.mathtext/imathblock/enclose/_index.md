---
title: enclose method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}

```python
def enclose(self):
    ...
```

## enclose(self, beginning_character, ending_character) {#char-char}

```python
def enclose(self, beginning_character, ending_character):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |

## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
이 블록의 하위 요소들을 괄호와 같은 지정된 문자 또는 다른 문자로 프레이밍하고 구분자를 사용하여 구분합니다.

### 반환값

지정된 문자를 프레이밍 및 구분자로 포함하는 [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter) 유형의 수학 요소

```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| beginning_character | **char** | 시작 문자(보통 왼쪽 괄호) |
| ending_character | **char** | 종료 문자(보통 오른쪽 괄호) |
| separator_character | **char** | 구분 문자 |

### 참고
* 클래스 [`IMathBlock`](/slides/python-net/ko/aspose.slides.mathtext/imathblock)
* 클래스 [`IMathDelimiter`](/slides/python-net/ko/aspose.slides.mathtext/imathdelimiter)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)