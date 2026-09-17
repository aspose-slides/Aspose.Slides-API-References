---
title: register_ink_effect_image method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Регистрирует изображение в коллекцию пользовательских изображений, используемых для имитации визуальных эффектов кистей с чернилами.
Эти изображения используются при рендеринге чернил с конкретными [`InkEffectType`](/slides/python-net/ru/aspose.slides.ink/inkeffecttype) значениями,
например, Galaxy, Rainbow и т.д. Предоставляя свои собственные изображения, вы можете контролировать, как выглядит каждый эффект чернил.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/ru/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/ru/aspose.slides/iimage) |  |

### Примечания

Этот метод позволяет заменять текстуры эффектов чернил по умолчанию на определённые пользователем,
что особенно полезно, когда ресурсы по умолчанию ограничены лицензией или недоступны во время выполнения.
Каждая зарегистрированная пара значений должна связывать значение [`InkEffectType`](/slides/python-net/ru/aspose.slides.ink/inkeffecttype) с соответствующим
объектом [`IImage`](/slides/python-net/ru/aspose.slides/iimage) (например, Bitmap или интерфейсом изображения Aspose).

### См. также
* класс [`IImage`](/slides/python-net/ru/aspose.slides/iimage)
* класс [`Ink`](/slides/python-net/ru/aspose.slides.ink/ink)
* перечисление [`InkEffectType`](/slides/python-net/ru/aspose.slides.ink/inkeffecttype)
* модуль [`aspose.slides.ink`](/slides/python-net/ru/aspose.slides.ink)
* библиотека [`Aspose.Slides`](/slides/python-net)