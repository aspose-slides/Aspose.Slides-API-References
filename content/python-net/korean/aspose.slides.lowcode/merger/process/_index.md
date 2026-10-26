---
title: process method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_file_names | **List[str]** | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| output_file_name | **str**** | 결과 병합된 프레젠테이션 파일의 출력 파일 이름입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일 이름이 유효하지 않거나 형식이 일치하지 않을 때 발생합니다. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_file_names | **List[str]** | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| output_stream | **io.RawIOBase** | 출력 스트림입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일 이름이 유효하지 않거나 형식이 일치하지 않을 때 발생합니다. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_file_names | **List[str]** | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| output_file_name | **str** | 결과 병합된 프레젠테이션 파일의 출력 파일 이름입니다. |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일 이름이 유효하지 않거나 형식이 일치하지 않을 때 발생합니다. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_file_names | **List[str]** | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| output_stream | **io.RawIOBase** | 출력 스트림입니다. |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 입력 파일 이름이 유효하지 않거나 형식이 일치하지 않을 때 발생합니다. |

### 또 다른 항목
* 클래스 [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions)
* 클래스 [`Merger`](/slides/python-net/ko/aspose.slides.lowcode/merger)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)