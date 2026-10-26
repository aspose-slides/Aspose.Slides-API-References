---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: واجهة عميل ويب للذكاء الاصطناعي.
type: docs
url: /ar/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

واجهة عميل ويب للذكاء الاصطناعي. تتيح هذه الواجهة استبدال نماذج اللغة المختلفة للذكاء الاصطناعي. من المفترض أن تُستخدم الفئات التي تُطبق هذه الواجهة جنبًا إلى جنب مع SlidesAIAgent.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام كائن HttpConnection المقدم ويرجع رسالة الاستجابة للتعليمات المعطاة. |
| [createConversation()](#createConversation--) | ينشئ مثيل محادثة. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

يرسل تعليمات محادثة إلى نموذج الذكاء الاصطناعي باستخدام كائن HttpConnection المقدم ويرجع رسالة الاستجابة للتعليمات المعطاة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| instruction | java.lang.String | التعليمات أو الرسالة التي سيعالجها نموذج الذكاء الاصطناعي. |

**القيمة المرجعة:**
java.lang.String - الرسالة التي أنشأها نموذج الذكاء الاصطناعي استجابةً للتعليمات المعطاة.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

ينشئ مثيل محادثة. على عكس المكالمات العادية للذكاء الاصطناعي، تحتفظ المحادثات بالسياق بالكامل.

**القيمة المرجعة:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - مثيل [IAIConversation](../../com.aspose.slides/iaiconversation)