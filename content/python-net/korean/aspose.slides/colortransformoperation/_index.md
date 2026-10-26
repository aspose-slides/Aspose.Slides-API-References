---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 열거형

색 변환 작업을 정의합니다.

ColorTransformOperation 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| TINT | 색을 색조합니다. 매개변수는 0(원래 색)과 1(흰색) 사이의 범위입니다. |
| SHADE | 색을 음영 처리합니다. 매개변수는 0(원래 색)과 1(검은색) 사이의 범위입니다. |
| COMPLEMENT | 색을 RGB 보색으로 변경합니다.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | 색을 반전된 색으로 변경합니다.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | 색을 동일한 명도와 회색으로 변경합니다. 매개변수는 무시됩니다. |
| SET_ALPHA | 색의 알파 구성 요소를 정의합니다. 매개변수는 0(투명)과 1(불투명) 사이의 범위입니다. |
| ADD_ALPHA | 매개변수 값을 색의 알파 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_ALPHA | 알파 구성 요소를 매개변수 값에 곱합니다. |
| SET_HUE | 색의 색상 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 360 사이의 범위입니다. |
| ADD_HUE | 매개변수 값을 색의 색상 구성 요소에 추가합니다. 매개변수는 -360과 360 사이의 범위입니다. |
| MULTIPLY_HUE | 색상 구성 요소를 매개변수 값에 곱합니다. |
| SET_SATURATION | 색의 채도 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다. |
| ADD_SATURATION | 매개변수 값을 색의 채도 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_SATURATION | 채도 구성 요소를 매개변수 값에 곱합니다. |
| SET_LUMINANCE | 색의 휘도 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다. |
| ADD_LUMINANCE | 매개변수 값을 색의 휘도 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_LUMINANCE | 휘도 구성 요소를 매개변수 값에 곱합니다. |
| SET_RED | 색의 빨간색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다. |
| ADD_RED | 매개변수 값을 색의 빨간색 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_RED | 빨간색 구성 요소를 매개변수에 곱합니다. |
| SET_GREEN | 색의 초록색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 1 사이의 범위입니다. |
| ADD_GREEN | 매개변수를 색의 초록색 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_GREEN | 초록색 구성 요소를 매개변수 값에 곱합니다. |
| SET_BLUE | 색의 파란색 구성 요소를 매개변수 값으로 변경합니다. 매개변수는 0과 360 사이의 범위입니다. |
| ADD_BLUE | 매개변수 값을 색의 파란색 구성 요소에 추가합니다. 매개변수는 -1과 1 사이의 범위입니다. |
| MULTIPLY_BLUE | 파란색 구성 요소를 매개변수 값에 곱합니다. |
| GAMMA | 감마 보정. 매개변수는 무시됩니다. |
| INVERSE_GAMMA | 역감마 보정. 매개변수는 무시됩니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)