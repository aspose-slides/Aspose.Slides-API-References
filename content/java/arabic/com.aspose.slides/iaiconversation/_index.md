---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: يمثل مثيلًا للمحادثة.
type: docs
url: /ar/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

يمثل مثيلًا للمحادثة. على عكس مكالمات الذكاء الاصطناعي العادية، تحتفظ المحادثات بالسياق بالكامل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | يرسل رسالة طلب محادثة تشمل السياق بالكامل ويعيد الاستجابة. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

ي отправляет رسالة طلب محادثة تشمل السياق بالكامل ويعيد الاستجابة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليمة أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي. |

**الإرجاع:**
java.lang.String - الرسالة التي يولدها نموذج الذكاء الاصطناعي استجابةً للتعليمة المعطاة ضمن سياق المحادثة.