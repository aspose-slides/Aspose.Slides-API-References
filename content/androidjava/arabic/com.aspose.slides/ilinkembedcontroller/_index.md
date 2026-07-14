---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /ar/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

واجهة رد نداء تُستَخدم لتحديد كيفية معالجة الكائن أثناء الحفظ.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | يحدد أين يجب تخزين الكائن. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | يُعيد عنوان URL لكائن خارجي. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | يحفظ الكائن الخارجي. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

يحدد أين يجب تخزين الكائن. تُستدعى هذه الطريقة مرة واحدة لكل معرف كائن. لا يُضمن عدم وجود كائنين ببيانات، واسم دلالي، ونوع محتوى متطابقة ولكن بمعرف مختلف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرف الكائن. هذا المعرف فريد طوال عملية الحفظ. |
| entityData | byte[] | البيانات الثنائية للكائن. يمكن أن يكون هذا المتغير null إذا لم تُولد البيانات الثنائية للكائن بعد. |
| semanticName | java.lang.String | نص قصير يصف معنى الكائن. قد يستخدم المتحكم هذا كجزء من اسم الكائن الخارجي، لكن مسؤولية التأكد من أن الأسماء فريدة وتحتوي فقط على الأحرف المسموح بها هي على المرسل. |
| contentType | java.lang.String | نوع MIME للكائن. |
| recomendedExtension | java.lang.String | امتداد اسم الملف المُوصى به لهذا النوع MIME. |

**القيمة المرجعة:**
int - القرار
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```

يُعيد عنوان URL لكائن خارجي. تُستدعى هذه الطريقة دائمًا إذا كان #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) قد أعاد [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) وقد تُستدعى إذا كان #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) قد أعاد [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) لكن الإدراج غير ممكن. يمكن استدعاؤها عدة مرات لنفس معرف الكائن.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرف الكائن. هذا المعرف فريد طوال عملية الحفظ. |
| referrer | int | معرف الكائن المرجعي أو 0 إذا كان الكائن مُشارًا إليه من المستند الجذر. قد يُستخدم لتوليد رابط نسبي. |

**القيمة المرجعة:**
java.lang.String - عنوان URL للكائن الخارجي أو null إذا كان يجب تجاهل هذا الكائن.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```

يحفظ الكائن الخارجي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرف الكائن. هذا المعرف فريد طوال عملية الحفظ. |
| entityData | byte[] | البيانات الثنائية للكائن. لا يمكن أن يكون هذا المتغير null. |