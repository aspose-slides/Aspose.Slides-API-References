---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Lägger till en ny anpassad xml-del.

### Returnerar

Skapade anpassad xml-del.



```python
def add(self, xml_string):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| xml_string | **str** | XML-strängen för den nya delen som ska läggas till. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString är tom eller xml-data är ogiltig. |


## add(self, xml_data) {#bytes}
Lägger till en ny anpassad xml-del.

### Returnerar

Skapade anpassad xml-del.



```python
def add(self, xml_data):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| xml_data | **bytes** | XML-data för den nya delen som ska läggas till. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData är tom eller ogiltig. |


## add(self, input_stream) {#iorawiobase}
Lägger till en ny anpassad xml-del.

### Returnerar

Skapade anpassad xml-del.



```python
def add(self, input_stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | inputStream med xml-data för den nya delen som ska läggas till. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data i inputStream är tom eller ogiltig. |



### Se även
* klass [`CustomXmlPartCollection`](/slides/python-net/sv/aspose.slides/customxmlpartcollection)
* klass [`ICustomXmlPart`](/slides/python-net/sv/aspose.slides/icustomxmlpart)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)