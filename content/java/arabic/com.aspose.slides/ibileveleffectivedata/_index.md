---
title: IBiLevelEffectiveData
second_title: Aspose.Slides لمرجع API لجافا
description: كائن غير قابل للتغيير يمثل تأثيرًا ثنائي المستوى (أسود/أبيض).
type: docs
url: /ar/com.aspose.slides/ibileveleffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

كائن غير قابل للتغيير يمثل تأثيرًا ذو مستويين (أسود/أبيض). يتم تحويل ألوان الإدخال التي يقل إنارتها عن القيمة الحدية المحددة إلى أسود. يتم تعيين ألوان الإدخال التي يتساوى إنارتها أو يزيد عن القيمة المحددة إلى أبيض. لا تتأثر قيم تأثير ألفا بهذا التأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | يرجع القيمة الحدية. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

يرجع القيمة الحدية. float للقراءة فقط.

**القيمة المرتجعة:**
float