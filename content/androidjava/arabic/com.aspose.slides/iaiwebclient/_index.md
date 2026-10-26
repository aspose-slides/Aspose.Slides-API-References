---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: واجهة عميل الويب للذكاء الاصطناعي.
type: docs
url: /ar/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

واجهة عميل الويب للذكاء الاصطناعي. تتيح هذه الواجهة استبدال نماذج لغة الذكاء الاصطناعي المختلفة. من المفترض استخدام الفئات التي تُطبق هذه الواجهة مع SlidesAIAgent.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | ترسل تعليمًا للدردشة إلى نموذج الذكاء الاصطناعي باستخدام كائن HttpConnection مقدم وتعيد رسالة الاستجابة للتعليم المعطى. |
| [createConversation()](#createConversation--) | إنشاء مثال محادثة. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

ترسل تعليمًا للدردشة إلى نموذج الذكاء الاصطناعي باستخدام كائن HttpConnection مقدم وتعيد رسالة الاستجابة للتعليم المعطى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليم أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي. |

**الإرجاع:**
java.lang.String - الرسالة التي يُنشئها نموذج الذكاء الاصطناعي استجابةً للتعليمات المعطاة.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

إنشاء مثال محادثة. على عكس استدعاءات الذكاء الاصطناعي العادية، تحتفظ المحادثات بالسياق الكامل.

**الإرجاع:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثال [IAIConversation](../../com.aspose.slides/iaiconversation).