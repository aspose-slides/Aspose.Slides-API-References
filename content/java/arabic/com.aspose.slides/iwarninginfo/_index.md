---
title: IWarningInfo
second_title: Aspose.Slides لمراجعة API لجافا
description: تمثّل واجهة أساسية لجميع التحذيرات.
type: docs
url: /ar/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

تمثّل واجهة أساسية لجميع التحذيرات.
## الطرق

| Method | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | إذا كان receiver غير فارغ، ينهي التحذير إلى receiver المحدد ويرمي استثناء AbortRequestedException إذا قرر receiver إلغاء العملية. |
| [getWarningType()](#getWarningType--) | إرجاع نوع التحذير. |
| [getDescription()](#getDescription--) | إرجاع وصف قابل للقراءة للإنسان لهذا التحذير. |

### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

إذا كان receiver غير فارغ، ينهي التحذير إلى receiver المحدد ويرمي استثناء AbortRequestedException إذا قرر receiver إلغاء العملية.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver كائن [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

إرجاع نوع التحذير. قراءة فقط [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**القيمة المرتجعة:**
int

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

إرجاع وصف قابل للقراءة للإنسان لهذا التحذير. قراءة فقط String.

**القيمة المرتجعة:**
java.lang.String