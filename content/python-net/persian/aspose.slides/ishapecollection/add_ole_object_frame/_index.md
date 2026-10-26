---
title: add_ole_object_frame method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
یک فریم OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

### بازگشت

[`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe) جدید ایجاد شده.

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات x فریم OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم OLE جدید، بر حسب نقطه. |
| width | **float** | عرض فریم OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم OLE جدید، بر حسب نقطه. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo) | اطلاعات دادهٔ OLE توکار ([`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)). |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
یک فریم OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌کند.

### بازگشت

[`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe) جدید ایجاد شده.

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات x فریم OLE جدید، بر حسب نقطه. |
| y | **float** | مختصات y فریم OLE جدید، بر حسب نقطه. |
| width | **float** | عرض فریم OLE جدید، بر حسب نقطه. |
| height | **float** | ارتفاع فریم OLE جدید، بر حسب نقطه. |
| class_name | **str** | نام کلاس شیء OLE. |
| path | **str** | مسیر فایل پیوند شده. <br/><br/>این مسیر به همان صورت در ارائه ذخیره می‌شود.<br/><br/>            اگر مسیر نسبی مشخص شود، فایل هنگام باز کردن<br/><br/>            ارائه از دایرکتوری متفاوت در دسترس نخواهد بود. |

### موارد مرتبط
* کلاس [`IOleEmbeddedDataInfo`](/slides/python-net/fa/aspose.slides/ioleembeddeddatainfo)
* کلاس [`IOleObjectFrame`](/slides/python-net/fa/aspose.slides/ioleobjectframe)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)