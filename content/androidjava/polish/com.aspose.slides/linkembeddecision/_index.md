---
title: LinkEmbedDecision
second_title: Aspose.Slides dla Androida – referencja API Java
description: Określa, jak obiekt będzie przetwarzany podczas zapisywania.
type: docs
url: /pl/com.aspose.slides/linkembeddecision/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Określa, jak obiekt będzie przetwarzany podczas zapisywania.
## Pola

| Pole | Opis |
| --- | --- |
| [Link](#Link) | Obiekt zostanie przechowany zewnętrznie, odwołany przez URL |
| [Embed](#Embed) | Obiekt powinien być osadzony w wygenerowanym pliku, jeśli to możliwe. |
| [Ignore](#Ignore) | Obiekt zostanie zignorowany. |
### Łącze {#Link}
```
public static final int Link
```

Obiekt zostanie przechowany zewnętrznie, odwołany przez URL

### Osadź {#Embed}
```
public static final int Embed
```

Obiekt powinien być osadzony w wygenerowanym pliku, jeśli to możliwe. Jeśli osadzenie jest niemożliwe, GetUrl zostanie wywołane i, w zależności od wyniku, obiekt zostanie odwołany przez URL lub zignorowany.

### Ignoruj {#Ignore}
```
public static final int Ignore
```

Obiekt zostanie zignorowany.