---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /ar/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

واجهة للصفوف التي تتلقى التحذير
## Methods

| الطريقة | الوصف |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | طريقة رد النداء التي تتلقى التحذير وتقرر ما إذا كان يجب إلغاء العملية. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

طريقة رد النداء التي تتلقى التحذير وتقرر ما إذا كان يجب إلغاء العملية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | التحذير المراد معالجته. |

**الإرجاع:**
int - قرار الإلغاء [ReturnAction](../../com.aspose.slides/returnaction).