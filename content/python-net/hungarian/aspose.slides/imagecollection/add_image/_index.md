---
title: add_image method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
Egy másik bemutatóból egy kép másolatát ad hozzá.

### Visszatér
Hozzáadott kép.

```python
def add_image(self, image_source):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | Forrás kép. |

## add_image(self, image) {#iimage}
Képet ad hozzá egy bemutatóhoz.

### Visszatér
Hozzáadott kép.

```python
def add_image(self, image):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/hu/aspose.slides/iimage) | Hozzáadandó kép. |

### Megjegyzés
Ez a metódus WMF/EMF metafájlokat raszteres PNG képpé konvertálja, mielőtt a bemutatóba illeszti.

## add_image(self, stream) {#iorawiobase}
Képet ad hozzá egy bemutatóhoz adatfolyamból.

### Visszatér
Hozzáadott kép.

```python
def add_image(self, stream):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Adatfolyam, amelyből a képet hozzáadja. |

### Megjegyzés
Ez a metódus WMF/EMF metafájlokat is hozzáadhat egy bemutatóhoz anélkül, hogy raszteres PNG képpé konvertálná őket.

## add_image(self, buffer) {#bytes}
Képet ad hozzá egy bemutatóhoz a megadott pufferból.

### Visszatér
Hozzáadott kép.

```python
def add_image(self, buffer):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| buffer | **bytes** | Puffer. |

## add_image(self, svg_image) {#isvgimage}
Képet ad hozzá egy bemutatóhoz SVG objektumból.

### Visszatér
Hozzáadott kép.

```python
def add_image(self, svg_image):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) | Svg kép objektum [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) |

### Kivétel
| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Amikor az svgImage paraméter None. |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehozza és hozzáad egy képet egy bemutatóhoz adatfolyamból.

### Visszatér
Hozzáadott [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage).

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Adatfolyam, amelyből a képfájlt hozzáadja. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | Az a viselkedés, amelyet az adatfolyamra alkalmaznak. |

### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* osztály [`ImageCollection`](/slides/python-net/hu/aspose.slides/imagecollection)
* osztály [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* osztály [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage)
* enumeráció [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)