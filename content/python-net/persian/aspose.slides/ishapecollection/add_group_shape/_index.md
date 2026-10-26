---
title: add_group_shape method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.
قاب گروه به‌طور خودکار تنظیم می‌شود تا هر شکلی که به آن اضافه شود را در برگیرد.

### Returns
[`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape) جدید ساخته شده.

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
یک شکل گروه جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به شکل‌های جداگانه تبدیل می‌نماید
و گروه حاصل را به انتهای مجموعهٔ شکل‌ها اضافه می‌کند.

### Returns
[`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape) جدید ساخته شده.

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage) حاوی محتوای برداری برای تبدیل به اشکال است. |
| x | **float** | مختصات x قاب گروه، بر حسب پوینت. |
| y | **float** | مختصات y قاب گروه، بر حسب پوینت. |
| width | **float** | عرض قاب گروه، بر حسب پوینت. |
| height | **float** | ارتفاع قاب گروه، بر حسب پوینت. |

### See Also
* class [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape)
* class [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* class [`ISvgImage`](/slides/python-net/fa/aspose.slides/isvgimage)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)