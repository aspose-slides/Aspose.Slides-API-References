---
title: save method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합으로 저장합니다.

```python
def save(self, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ko/aspose.slides.export.xaml/ixamloptions) | XAML 형식 옵션. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다.

```python
def save(self, fname, format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| fname | **str** | 생성된 파일의 경로. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다.

```python
def save(self, stream, format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 출력 스트림. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
프레젠테이션의 모든 슬라이드를 지정된 형식과 추가 옵션으로 스트림에 저장합니다.

```python
def save(self, stream, format, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 출력 스트림. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) | 추가 형식 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 암호화된 파일을 Office 2007-2010 형식이 아닌 형식으로 저장하려고 시도할 경우 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다.

```python
def save(self, fname, slides, format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| fname | **str** | 생성된 파일의 경로. |
| slides | **List[int]** | 슬라이드 위치를 나타내는 배열이며, 1부터 시작합니다. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream 또는 slides 매개변수가 None인 경우. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 지원되지 않는 SaveFormat이 사용된 경우(예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP). |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식으로 스트림에 저장합니다.

```python
def save(self, stream, slides, format):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 출력 스트림. |
| slides | **List[int]** | 슬라이드 위치를 나타내는 배열이며, 1부터 시작합니다. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다.

```python
def save(self, fname, slides, format, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| fname | **str** | 생성된 파일의 경로. |
| slides | **List[int]** | 슬라이드 위치를 나타내는 배열이며, 1부터 시작합니다. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) | 추가 형식 옵션. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식으로 스트림에 저장합니다.

```python
def save(self, stream, slides, format, options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 출력 스트림. |
| slides | **List[int]** | 슬라이드 위치를 나타내는 배열이며, 1부터 시작합니다. |
| format | [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat) | 내보낸 데이터의 형식. |
| options | [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions) | 추가 형식 옵션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream 또는 slides 매개변수가 None인 경우. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 지원되지 않는 SaveFormat이 사용된 경우(예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP). |

### 참고
* 클래스 [`ISaveOptions`](/slides/python-net/ko/aspose.slides.export/isaveoptions)
* 클래스 [`IXamlOptions`](/slides/python-net/ko/aspose.slides.export.xaml/ixamloptions)
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 열거형 [`SaveFormat`](/slides/python-net/ko/aspose.slides.export/saveformat)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)