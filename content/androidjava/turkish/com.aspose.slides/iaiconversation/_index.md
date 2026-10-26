---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /tr/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Temsili bir konuşma örneği. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı tutar.
## Yöntemler

| Method | Description |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Tam bağlamı içeren bir konuşma isteği mesajı gönderir ve yanıt döndürür. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Tam bağlamı içeren bir konuşma isteği mesajı gönderir ve yanıt döndürür.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj. |

**Dönüş Değeri:**
java.lang.String - Verilen talimat için konuşma bağlamı içinde AI modeli tarafından oluşturulan mesaj.