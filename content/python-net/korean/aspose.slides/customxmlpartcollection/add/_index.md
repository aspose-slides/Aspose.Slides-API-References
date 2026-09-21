---
title: add method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
새로운 사용자 정의 XML 파트를 추가합니다.

### 반환

새로운 사용자 정의 XML 파트가 생성되었습니다.



```python
def add(self, xml_string):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| xml_string | **str** | 추가될 새 파트의 XML 문자열입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString이 `None`입니다. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString이 비어 있거나 XML 데이터가 유효하지 않습니다. |


## add(self, xml_data) {#bytes}
새로운 사용자 정의 XML 파트를 추가합니다.

### 반환

새로운 사용자 정의 XML 파트가 생성되었습니다.



```python
def add(self, xml_data):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| xml_data | **bytes** | 추가될 새 파트의 XML 데이터입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData가 `None`입니다. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData가 비어 있거나 유효하지 않습니다. |


## add(self, input_stream) {#iorawiobase}
새로운 사용자 정의 XML 파트를 추가합니다.

### 반환

새로운 사용자 정의 XML 파트가 생성되었습니다.



```python
def add(self, input_stream):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | 추가될 새 파트의 XML 데이터를 포함하는 inputStream입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream이 `None`입니다. |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream의 데이터가 비어 있거나 유효하지 않습니다. |



### 참조
* 클래스 [`CustomXmlPartCollection`](/slides/python-net/ko/aspose.slides/customxmlpartcollection)
* 클래스 [`ICustomXmlPart`](/slides/python-net/ko/aspose.slides/icustomxmlpart)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)