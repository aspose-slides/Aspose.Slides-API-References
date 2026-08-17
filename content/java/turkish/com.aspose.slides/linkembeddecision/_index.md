---
title: LinkEmbedDecision
second_title: Aspose.Slides Java API Referansı
description: Nesnenin kaydedilirken nasıl işleneceğini belirler.
type: docs
url: /tr/com.aspose.slides/linkembeddecision/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Nesnenin kaydedilirken nasıl işleneceğini belirler.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Link](#Link) | Nesne harici olarak saklanacak, URL ile referans verilecek |
| [Embed](#Embed) | Nesne mümkünse oluşturulan dosyaya gömülmelidir. |
| [Ignore](#Ignore) | Nesne yoksayılacak. |
### Bağlantı {#Link}
```
public static final int Link
```

Nesne harici olarak saklanacak, URL ile referans verilecek

### Göm {#Embed}
```
public static final int Embed
```

Nesne mümkünse oluşturulan dosyaya gömülmelidir. Eğer gömme mümkün değilse, GetUrl çağrılacak ve sonuca göre nesne URL ile referans verilecek ya da yoksayılacak.

### Yoksay {#Ignore}
```
public static final int Ignore
```

Nesne yoksayılacak.