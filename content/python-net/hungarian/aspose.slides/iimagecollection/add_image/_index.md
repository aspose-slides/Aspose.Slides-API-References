---
title: add_image method
second_title: Aspose.Slides Python számára .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Képet ad hozzá egy prezentációhoz.

### Returns
Hozzáadott kép.

```python
def add_image(self, image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/hu/aspose.slides/iimage) | Hozzáadandó kép. |

### Remarks
Ez a metódus a WMF/EMF metafájlokat raszteres PNG képpé konvertálja, mielőtt a prezentációba beszúrja.



## add_image(self, stream) {#iorawiobase}
Képet ad hozzá egy prezentációhoz egy adatfolyamból.

### Returns
Hozzáadott kép.

```python
def add_image(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az adatfolyam, amelyből a képet hozzáadja. |

### Remarks
Ez a metódus WMF/EMF metafájlokat adhat hozzá a prezentációhoz anélkül, hogy raszteres PNG képpé konvertálná őket.



## add_image(self, buffer) {#bytes}
Képet ad hozzá egy prezentációhoz a megadott pufferből.

### Returns
Hozzáadott kép.

```python
def add_image(self, buffer):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| buffer | **bytes** | Puffer. |


## add_image(self, image_source) {#ippimage}
Másolatot ad hozzá egy képről egy másik prezentációból.

### Returns
Hozzáadott kép.

```python
def add_image(self, image_source):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage) | Forráskép. |


## add_image(self, svg_image) {#isvgimage}
Képet ad hozzá egy prezentációhoz SVG objektumból.

### Returns
Hozzáadott kép.

```python
def add_image(self, svg_image):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) | SVG kép objektum [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage) |

### Kivételek

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kivétel dobódik, ha az svgImage paraméter None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Létrehoz és hozzáad egy képet a prezentációhoz egy adatfolyamból.

### Returns
Hozzáadott [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage).

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az adatfolyam, amelyből a képfájlt hozzáadja. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior) | Az a viselkedés, amelyet az adatfolyamra alkalmazni kell. |


### Lásd még
* class [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* class [`IImageCollection`](/slides/python-net/hu/aspose.slides/iimagecollection)
* class [`IPPImage`](/slides/python-net/hu/aspose.slides/ippimage)
* class [`ISvgImage`](/slides/python-net/hu/aspose.slides/isvgimage)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/hu/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)