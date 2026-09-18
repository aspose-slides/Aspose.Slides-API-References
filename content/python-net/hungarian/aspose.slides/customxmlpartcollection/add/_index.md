---
title: add method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
Új egyéni XML részt ad hozzá.

### Returns
Létrehozott egyéni XML rész.

```python
def add(self, xml_string):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| xml_string | **str** | Az xml_string a hozzáadandó új rész XML karakterlánca. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString üres vagy xml-data érvénytelen. |

## add(self, xml_data) {#bytes}
Új egyéni XML részt ad hozzá.

### Returns
Létrehozott egyéni XML rész.

```python
def add(self, xml_data):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| xml_data | **bytes** | Az xml_data a hozzáadandó új rész XML adata. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData üres vagy érvénytelen. |

## add(self, input_stream) {#iorawiobase}
Új egyéni XML részt ad hozzá.

### Returns
Létrehozott egyéni XML rész.

```python
def add(self, input_stream):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | Az input_stream a hozzáadandó új rész XML adataival rendelkező inputStream. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Az adat az inputStream-ben üres vagy érvénytelen. |

### Lásd még
* osztály [`CustomXmlPartCollection`](/slides/python-net/hu/aspose.slides/customxmlpartcollection)
* osztály [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)