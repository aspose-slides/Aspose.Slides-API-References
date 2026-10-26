---
title: set_size method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/slidesize/set_size/
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
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype) | Режим масштабирования содержимого. |

### Примечания

Назначение любого значения, отличного от [`SlideSizeType.CUSTOM`](/slides/python-net/ru/aspose.slides/slidesizetype/CUSTOM), корректирует [`SlideSize.size`](/slides/python-net/ru/aspose.slides/slidesize/size) в соответствии с выбранным типом, сохраняя [`SlideSize.orientation`](/slides/python-net/ru/aspose.slides/slidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Явно задаёт размеры слайда и масштабирует существующее содержимое.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| width | **float** | Новая ширина слайда в пунктах. |
| height | **float** | Новая высота слайда в пунктах. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype) | Режим масштабирования содержимого. |

### Примечания

Это сбрасывает свойство [`SlideSize.type`](/slides/python-net/ru/aspose.slides/slidesize/type) до [`SlideSizeType.CUSTOM`](/slides/python-net/ru/aspose.slides/slidesizetype/CUSTOM) и устанавливает [`SlideSize.orientation`](/slides/python-net/ru/aspose.slides/slidesize/orientation).

### См. также
* класс [`SlideSize`](/slides/python-net/ru/aspose.slides/slidesize)
* перечисление [`SlideSizeScaleType`](/slides/python-net/ru/aspose.slides/slidesizescaletype)
* перечисление [`SlideSizeType`](/slides/python-net/ru/aspose.slides/slidesizetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)