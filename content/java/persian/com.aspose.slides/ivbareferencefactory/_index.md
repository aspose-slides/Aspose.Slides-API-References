---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /fa/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

اجازه می‌دهد تا مراجع پروژه VBA را از طریق رابط COM ایجاد کند
## متدها

| متد | توضیح |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | یک مرجع کتابخانه نوع OLE Automation جدید ایجاد می‌کند. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

یک مرجع کتابخانه نوع OLE Automation جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام مرجع پروژه VBA String |
| libid | java.lang.String | شناسه یک کتابخانه نوع Automation String |

**مقدار برگشتی:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - مرجع کتابخانه نوع OLE Automation جدید [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)