---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Returnerar ett Thumbnail Image-objekt (20% av verklig storlek).


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Returnerar ett Thumbnail Image-objekt med angiven storlek.

### Returnerar

Image-objekt.



```python
def get_image(self, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Returnerar ett Thumbnail tiff Image-objekt med angivna parametrar.

### Returnerar

Image-objekt.



```python
def get_image(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/sv/aspose.slides.export/itiffoptions) | Tiff-alternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när options.SlideLayoutOption är NotesCommentsLayoutOptions och dess egenskap NotesPosition får värdet NotesPositions.BottomFull. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Returnerar ett Thumbnail Image-objekt.

### Returnerar

Image-objekt.



```python
def get_image(self, options):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när notesCommentsLayouting.NotesPosition får värdet NotesPositions.BottomFull. |


## get_image(self, scale_x, scale_y) {#float-float}
Returnerar ett Thumbnail Image-objekt med anpassad skalning.

### Returnerar

IImage-objekt.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | **float** | Värdet som detta Thumbnail ska skalas med i x-axelns riktning. |
| scale_y | **float** | Värdet som detta Thumbnail ska skalas med i y-axelns riktning. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Returnerar ett Thumbnail Image-objekt med angiven storlek.

### Returnerar

Image-objekt.



```python
def get_image(self, options, image_size):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| image_size | [`Size`](/slides/python-net/sv/aspose.slides/size) | Storlek på bilden som ska skapas. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när options.SlideLayoutOption är NotesCommentsLayoutOptions och dess egenskap NotesPosition får värdet NotesPositions.BottomFull. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Returnerar ett Thumbnail Image-objekt med anpassad skalning.

### Returnerar

Bitmap-objekt.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions) | Renderingsalternativ. |
| scale_x | **float** | Värdet som detta Thumbnail ska skalas med i x-axelns riktning. |
| scale_y | **float** | Värdet som detta Thumbnail ska skalas med i y-axelns riktning. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Kastas när notesCommentsLayouting.NotesPosition får värdet NotesPositions.BottomFull. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`IRenderingOptions`](/slides/python-net/sv/aspose.slides.export/irenderingoptions)
* klass [`ITiffOptions`](/slides/python-net/sv/aspose.slides.export/itiffoptions)
* klass [`Slide`](/slides/python-net/sv/aspose.slides/slide)
* klass [`Size`](/slides/python-net/sv/aspose.slides/size)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)