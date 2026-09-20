---
title: get_images method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Vrací objekty Thumbnail Image pro všechny snímky prezentace.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Vrací objekty Thumbnail Bitmap pro určené snímky prezentace.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options, slides):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Vrací objekty Thumbnail Image pro všechny snímky prezentace se zadanou velikostí.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| image_size | **aspose.slides.Size** | Velikost obrázku, který se má vytvořit. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním škálováním.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail v ose x škálovat. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail v ose y škálovat. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Vrací objekty Thumbnail Image pro určené snímky prezentace se zadanou velikostí.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| image_size | **aspose.slides.Size** | Velikost obrázku, který se má vytvořit. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastním škálováním.

### Vrací

Objekty Bitmap.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions) | Možnosti vykreslování. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| scale_x | **float** | Hodnota, o kterou se má tento Thumbnail v ose x škálovat. |
| scale_y | **float** | Hodnota, o kterou se má tento Thumbnail v ose y škálovat. |



### Viz také
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* třída [`IRenderingOptions`](/slides/python-net/cs/aspose.slides.export/irenderingoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)