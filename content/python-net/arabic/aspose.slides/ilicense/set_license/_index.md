---
title: set_license method
second_title: Aspose.Slides للغة بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
يقوم بترخيص المكوّن.

```python
def set_license(self, license_name):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| license_name | **str** | يمكن أن يكون اسم ملف كامل أو مختصر أو اسم مورد مضمّن.<br/><br/>            استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

### ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.
2. مجلد تجميع المكوّن.
3. مجلد تجميع العميل المستدعي.
4. مجلد تجميع الدخول.
5. مورد مضمّن في تجميع العميل المستدعي.

**ملاحظة:** في .NET Compact Framework، يحاول العثور على الترخيص فقط في هذه المواقع:

1. مسار صريح.
2. مورد مضمّن في تجميع العميل المستدعي.

## set_license(self, stream) {#iorawiobase}
يقوم بترخيص المكوّن.

```python
def set_license(self, stream):
    ...
```

| معامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق يحتوي على الترخيص. |

### ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من دفق.

### انظر أيضاً
* فئة [`ILicense`](/slides/python-net/ar/aspose.slides/ilicense)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)