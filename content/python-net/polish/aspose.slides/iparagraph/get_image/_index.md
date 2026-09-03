---
title: get_image method
second_title: Aspose.Slides dla Pythona przez .NET Odwołanie API
description: 
type: docs
url: /pl/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Zwraca obraz akapitu.

### Zwraca

Obraz zawierający renderowany akapit, lub **None**
             jeśli akapit nie może zostać odnaleziony w swojej kolekcji nadrzędnej, nie ma prawidłowych
             granic renderowania lub wystąpił błąd podczas renderowania obrazu.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Zwraca obraz akapitu w określonej skali.

### Zwraca

Obraz zawierający renderowany akapit, oraz **None**
             jeśli akapit nie może zostać odnaleziony w swojej kolekcji nadrzędnej, nie ma prawidłowych
             granic renderowania lub wystąpił błąd podczas renderowania obrazu.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| scale_x | **float** | Poziomy współczynnik skali stosowany do obrazu akapitu. |
| scale_y | **float** | Pionowy współczynnik skali stosowany do obrazu akapitu. |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* klasa [`IParagraph`](/slides/python-net/pl/aspose.slides/iparagraph)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)