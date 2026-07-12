---
title: LinkEmbedDecision
second_title: Aspose.Slides Android için Java API Referansı
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
| [Link](#Link) | Nesne dışarıda depolanacak, URL ile referans verilecektir |
| [Embed](#Embed) | Nesne mümkünse oluşturulan dosyaya gömülmelidir. |
| [Ignore](#Ignore) | Nesne yok sayılacak. |
### Bağlantı {#Link}
```
public static final int Link
```


Nesne dışarıda depolanacak, URL ile referans verilecektir

### Göm {#Embed}
```
public static final int Embed
```


Nesne mümkünse oluşturulan bir dosyaya gömülmelidir. Gömme mümkün olmadığında, GetUrl çağrılacak ve sonuca bağlı olarak nesne URL ile referans verilecek ya da yok sayılacaktır.

### Yok Say {#Ignore}
```
public static final int Ignore
```


Nesne yok sayılacak.