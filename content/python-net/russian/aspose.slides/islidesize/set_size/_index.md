---
title: set_size method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Устанавливает размер слайда по типу и масштабирует существующее содержимое.


```python
def set_size(self, type, scale_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/ru/aspose.slides/slidesizetype) | Предопределённый размер слайда, который следует применить. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype) | Режим масштабирования содержимого, который следует использовать. |

### Примечания

Назначение любого значения, отличного от [`SlideSizeType.CUSTOM`](/slides/python-net/ru/aspose.slides/slidesizetype/CUSTOM), изменяет [`ISlideSize.size`](/slides/python-net/ru/aspose.slides/islidesize/size) в зависимости от выбранного типа, при сохранении [`ISlideSize.orientation`](/slides/python-net/ru/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Устанавливает размеры слайда явно и масштабирует существующее содержимое.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| width | **float** | Новая ширина слайда в пунктах. |
| height | **float** | Новая высота слайда в пунктах. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype) | Режим масштабирования содержимого, который следует использовать. |

### Примечания

Это сбрасывает свойство [`ISlideSize.type`](/slides/python-net/ru/aspose.slides/islidesize/type) к [`SlideSizeType.CUSTOM`](/slides/python-net/ru/aspose.slides/slidesizetype/CUSTOM) и устанавливает [`ISlideSize.orientation`](/slides/python-net/ru/aspose.slides/islidesize/orientation).



### Смотрите также
* класс [`ISlideSize`](/slides/python-net/ru/aspose.slides/islidesize)
* перечисление [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype)
* перечисление [`SlideSizeType`](/slides/python-net/ru/aspose.slides/slidesizetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)