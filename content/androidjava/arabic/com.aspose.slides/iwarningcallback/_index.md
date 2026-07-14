---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for classes which receive warning
type: docs
url: /ar/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

واجهة للفئات التي تتلقى التحذير
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | طريقة النداء التي تتلقى التحذير وتقرر ما إذا كان يجب إلغاء العملية. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

طريقة النداء التي تتلقى التحذير وتقرر ما إذا كان يجب إلغاء العملية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | التحذير للمعالجة. |

**القيمة المرجعة:**
int - قرار الإلغاء [ReturnAction](../../com.aspose.slides/returnaction).