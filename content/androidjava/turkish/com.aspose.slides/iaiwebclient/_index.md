---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web istemci arayüzü.
type: docs
url: /tr/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web istemci arayüzü. Bu arayüz, farklı AI dil modellerinin yer değiştirmesini sağlar. Bu arayüzü uygulayan sınıflar SlidesAIAgent ile birlikte kullanılmalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sağlanan bir HttpConnection örneğini kullanarak AI modeline bir sohbet yönergesi gönderir ve verilen yönergeye yanıt mesajını döndürür. |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Sağlanan bir HttpConnection örneğini kullanarak AI modeline bir sohbet yönergesi gönderir ve verilen yönergeye yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek yönerge veya mesaj. |

**Döndürür:**
java.lang.String - Verilen yönergeye yanıt olarak AI modeli tarafından oluşturulan mesaj.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.

**Döndürür:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Bir [IAIConversation](../../com.aspose.slides/iaiconversation) örneği.