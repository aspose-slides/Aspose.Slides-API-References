---
title: set_license method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
يقوم بترخيص المكوّن.


```python
def set_license(self, license_name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| license_name | **str** | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مدمج.<br/><br/> استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

### ملاحظات

يحاول العثور على الترخيص في المواقع التالية:


1. مسار صريح.

2. مجلد تجميع المكوّن.

3. مجلد تجميع الاستدعاء للعميل.

4. مجلد تجميع الدخول.

5. مورد مدمج في تجميع الاستدعاء للعميل.

**ملاحظة:** في .NET Compact Framework، يحاول العثور على الترخيص فقط في هذه المواقع:


1. مسار صريح.

2. مورد مدمج في تجميع الاستدعاء للعميل.


## set_license(self, stream) {#iorawiobase}
يقوم بترخيص المكوّن.


```python
def set_license(self, stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق يحتوي على الترخيص. |

### ملاحظات

استخدم هذه الطريقة لتحميل ترخيص من دفق.



### انظر أيضًا
* فئة [`License`](/slides/python-net/ar/aspose.slides/license)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)