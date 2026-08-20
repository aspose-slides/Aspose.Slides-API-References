---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /ar/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

واجهة رد نداء تُستخدم لتحديد كيفية معالجة الكائن أثناء الحفظ.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | Determines where object should be stored. |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | Returns an URL to an external object. |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | Saves external object. |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


يحدد أين يجب تخزين الكائن. تُستدعى هذه الطريقة مرة واحدة لكل معرّف كائن. لا يُضمن عدم وجود كائنين ببيانات، semanticName، وcontentType متطابقة ولكن بمعرّف مختلف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرّف الكائن. هذا المعرف فريد على مستوى عملية الحفظ. |
| entityData | byte[] | البيانات الثنائية للكائن. يمكن أن تكون هذه القيمة null إذا لم يتم توليد البيانات الثنائية بعد. |
| semanticName | java.lang.String | نص قصير يصف معنى الكائن. قد يستخدم المتحكم هذا كجزء من اسم الكائن الخارجي، لكن الأمر متروك للمرسل لضمان أن الأسماء ستكون فريدة وتحتوي فقط على الأحرف المسموح بها. |
| contentType | java.lang.String | نوع MIME للكائن. |
| recomendedExtension | java.lang.String | امتداد اسم الملف الموصى به لهذا النوع MIME. |

**الإرجاع:**
int - قرار
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


يرجع عنوان URL إلى كائن خارجي. تُستدعى هذه الطريقة دائماً إذا أرجعت \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) القيمة [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) وقد تُستدعى إذا أرجعت \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) القيمة [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) ولكن لا يمكن تضمينه. يمكن استدعاؤها عدة مرات لنفس معرّف الكائن.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرّف الكائن. هذا المعرف فريد على مستوى عملية الحفظ. |
| referrer | int | معرّف الكائن المُشير أو 0 إذا كان الكائن مُشارًا إليه من المستند الجذر. قد يُستخدم لتوليد رابط نسبي. |

**الإرجاع:**
java.lang.String - عنوان URL للكائن الخارجي أو null إذا كان يجب تجاهل هذا الكائن.
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


يحفظ الكائن الخارجي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | int | معرّف الكائن. هذا المعرف فريد على مستوى عملية الحفظ. |
| entityData | byte[] | البيانات الثنائية للكائن. لا يمكن أن تكون هذه القيمة null. |