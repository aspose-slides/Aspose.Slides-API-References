---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: يمثل مثال محادثة.
type: docs
url: /ar/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

يمثل مثال محادثة. على عكس مكالمات الذكاء الاصطناعي العادية، تحتفظ المحادثات بكامل السياق.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | يرسل رسالة طلب محادثة تشمل السياق بالكامل ويعيد الاستجابة. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

يرسل رسالة طلب محادثة تشمل السياق بالكامل ويعيد الاستجابة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليمات أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي. |

**القيمة المرجعة:**
java.lang.String - الرسالة التي يولدها نموذج الذكاء الاصطناعي استجابةً للتعليمات المعطاة ضمن سياق المحادثة.