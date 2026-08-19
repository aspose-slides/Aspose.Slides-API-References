---
title: VbaReferenceFactory
second_title: مرجع API Aspose.Slides برای جاوا
description: اجازه می‌دهد تا ارجاعات پروژه VBA را از طریق رابط COM ایجاد کند
type: docs
url: /fa/com.aspose.slides/vbareferencefactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

به شما امکان ایجاد ارجاعات پروژه VBA از طریق رابط COM را می‌دهد
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [getInstance()](#getInstance--) | نمونه ثابت کارخانه ارجاعات پروژه VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | یک ارجاع جدید به کتابخانهٔ نوع OLE Automation ایجاد می‌کند. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA project references factory static instance. فقط خواندنی [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**بازگشت:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


یک ارجاع جدید به کتابخانهٔ نوع OLE Automation ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**بازگشت:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - ارجاع جدید به کتابخانهٔ نوع OLE Automation