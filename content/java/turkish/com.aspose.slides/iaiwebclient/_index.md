---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI Web client interface.
type: docs
url: /tr/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web istemci arabirimi. Bu arabirim, farklı AI dil modellerinin yerine kullanılmasını sağlar. Bu arabirimi uygulayan sınıflar SlidesAIAgent ile birlikte kullanılmalıdır.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sağlanan bir HttpConnection örneği kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür. |
| [createConversation()](#createConversation--) | Bir konuşma örneği oluşturur. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Sağlanan bir HttpConnection örneği kullanarak AI modeline bir sohbet talimatı gönderir ve verilen talimata yanıt mesajını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| instruction | java.lang.String | AI modeli tarafından işlenecek talimat veya mesaj. |

**Döndürür:**
java.lang.String - AI modelinin verilen talimata yanıt olarak oluşturduğu mesaj.
### createConversation() {#createConversation--}
```
public abstract IIAConversation createConversation()
```

Bir konuşma örneği oluşturur. Normal AI çağrılarının aksine, konuşmalar tüm bağlamı korur.

**Döndürür:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Bir [IAIConversation](../../com.aspose.slides/iaiconversation) örneği.