---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
새 사용자 지정 xml 파트를 추가합니다.

### 반환값

사용자 지정 xml 파트가 생성되었습니다.



```python
def add(self, xml_data):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| xml_data | **bytes** | 추가될 새 파트의 xml 데이터입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData는 `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData는 비어 있거나 유효하지 않습니다. |


## add(self, xml_string) {#str}
새 사용자 지정 xml 파트를 추가합니다.

### 반환값

사용자 지정 xml 파트가 생성되었습니다.



```python
def add(self, xml_string):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| xml_string | **str** | 추가될 새 파트의 xml 문자열입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString는 `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString는 비어 있거나 xml-data가 유효하지 않습니다. |


## add(self, input_stream) {#iorawiobase}
새 사용자 지정 xml 파트를 추가합니다.

### 반환값

사용자 지정 xml 파트가 생성되었습니다.



```python
def add(self, input_stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | 추가될 새 파트의 xml 데이터를 포함하는 inputStream입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream은 `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream의 데이터가 비어 있거나 Sinvalid. |



### 또한 보기
* 클래스 [`ICustomXmlPart`](/slides/python-net/ko/aspose.slides/icustomxmlpart)
* 클래스 [`ICustomXmlPartCollection`](/slides/python-net/ko/aspose.slides/icustomxmlpartcollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)