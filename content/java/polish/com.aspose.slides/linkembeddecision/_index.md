---
title: LinkEmbedDecision
second_title: Aspose.Slides dla Java – dokumentacja API
description: Określa, jak obiekt będzie przetwarzany podczas zapisywania.
type: docs
url: /pl/com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Określa, jak obiekt będzie przetwarzany podczas zapisywania.
## Pola

| Pole | Opis |
| --- | --- |
| [Link](#Link) | Obiekt zostanie przechowany zewnętrznie, odwołany przez URL |
| [Embed](#Embed) | Obiekt powinien być osadzony w generowanym pliku, jeśli to możliwe. |
| [Ignore](#Ignore) | Obiekt zostanie zignorowany. |
### Połączenie {#Link}
```
public static final int Link
```


Obiekt zostanie przechowany zewnętrznie, odwołany przez URL

### Osadzenie {#Embed}
```
public static final int Embed
```


Obiekt powinien być osadzony w generowanym pliku, jeśli to możliwe. Jeśli osadzanie jest niemożliwe, zostanie wywołane GetUrl i w zależności od wyniku, obiekt będzie odwołany przez URL lub zignorowany.

### Ignoruj {#Ignore}
```
public static final int Ignore
```


Obiekt zostanie zignorowany.