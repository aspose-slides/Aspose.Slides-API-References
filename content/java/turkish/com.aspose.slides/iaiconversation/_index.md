---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Represents a conversation instance.
type: docs
url: /tr/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Bir konuşma örneğini temsil eder. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Tüm bağlamı içeren konuşma isteği mesajını gönderir ve yanıt döndürür. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Tüm bağlamı içeren konuşma isteği mesajını gönderir ve yanıt döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj. |

**Döndürür:**
java.lang.String - Verilen talimat ve konuşma bağlamı içinde AI modeli tarafından üretilen mesaj.