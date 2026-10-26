---
title: LinkEmbedDecision
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa, w jaki sposób obiekt będzie przetwarzany podczas zapisywania.
type: docs
weight: 911
url: /pl/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Określa, jak obiekt będzie przetwarzany podczas zapisywania.

```cpp
enum class LinkEmbedDecision
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| Link | 0 | Obiekt zostanie przechowywany zewnętrznie, odwoływany przez URL |
| Embed | 1 | Obiekt powinien być osadzony w generowanym pliku, jeśli to możliwe. Jeśli osadzanie jest niemożliwe, zostanie wywołane GetUrl i w zależności od wyniku, obiekt zostanie odwołany przez URL lub zignorowany. |
| Ignore | 2 | Obiekt zostanie zignorowany. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)