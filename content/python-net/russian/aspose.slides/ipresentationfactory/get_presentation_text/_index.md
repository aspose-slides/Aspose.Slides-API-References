---
title: get_presentation_text method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ipresentationfactory/get_presentation_text/
weight: 30
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
Получает необработанный текст со слайдов

### Возвращает

Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов



```python
def get_presentation_text(self, file, mode):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| file | **str** | Входной файл |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ru/aspose.slides/textextractionarrangingmode) | Режим извлечения |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
Получает необработанный текст со слайдов

### Возвращает

Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов



```python
def get_presentation_text(self, stream, mode):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Входной поток |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ru/aspose.slides/textextractionarrangingmode) | Режим извлечения |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
Получает необработанный текст со слайдов

### Возвращает

Экземпляр PresentationText, содержащий массив SlideText, представляющий необработанный текст слайдов



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Входной поток |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/ru/aspose.slides/textextractionarrangingmode) | Режим извлечения |
| options | [`ILoadOptions`](/slides/python-net/ru/aspose.slides/iloadoptions) | Параметры загрузки |



### См. также
* класс [`ILoadOptions`](/slides/python-net/ru/aspose.slides/iloadoptions)
* класс [`IPresentationFactory`](/slides/python-net/ru/aspose.slides/ipresentationfactory)
* класс [`IPresentationText`](/slides/python-net/ru/aspose.slides/ipresentationtext)
* перечисление [`TextExtractionArrangingMode`](/slides/python-net/ru/aspose.slides/textextractionarrangingmode)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)