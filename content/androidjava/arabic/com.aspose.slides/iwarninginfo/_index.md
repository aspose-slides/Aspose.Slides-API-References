---
title: IWarningInfo
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: تمثِّل واجهةً أساسيةً لجميع التحذيرات.
type: docs
url: /ar/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

تمثِّل واجهةً أساسيةً لجميع التحذيرات.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | إذا كان receiver غير null ينهي التحذير إلى receiver محدد ويطرح AbortRequestedException إذا قرر receiver إلغاء عملية. |
| [getWarningType()](#getWarningType--) | يعيد نوع التحذير. |
| [getDescription()](#getDescription--) | يعيد وصفًا قابلًا للقراءة للإنسان لهذا التحذير. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

إذا كان receiver غير null ينهي التحذير إلى receiver محدد ويطرح AbortRequestedException إذا قرر receiver إلغاء عملية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | كائن receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

يعيد نوع التحذير. قراءة فقط [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**الإرجاع:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

يعيد وصفًا قابلًا للقراءة للإنسان لهذا التحذير. قراءة فقط String.

**الإرجاع:**
java.lang.String