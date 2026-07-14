---
title: IBiLevelEffectiveData
second_title: Aspose.Slides للـ Android عبر مرجع واجهة برمجة التطبيقات Java
description: كائن غير قابل للتغيير يمثل تأثيرًا ثنائي المستوى (أسود/أبيض).
type: docs
url: /ar/com.aspose.slides/ibileveleffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

كائن غير قابل للتغيير يمثل تأثيرًا ثنائي المستوى (أسود/أبيض). تُغيّر ألوان الإدخال التي يقل لمعانها عن قيمة العتبة المحددة إلى الأسود. تُعيّن ألوان الإدخال التي يساوي أو يزيد لمعانها عن القيمة المحددة إلى الأبيض. قيم تأثير ألفا لا تتأثر بهذا التأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getThreshold()](#getThreshold--) | يعيد قيمة العتبة. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


يعيد قيمة العتبة. للقراءة فقط float.

**الإرجاع:**
float