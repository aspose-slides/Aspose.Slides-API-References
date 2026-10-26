---
title: CompressionLevel
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa poziomy kompresji ZIP dla pliku OpenXML. Wyższe poziomy zapewniają lepszą kompresję kosztem wolniejszego przetwarzania.
type: docs
weight: 846
url: /pl/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Określa poziomy kompresji ZIP dla pliku OpenXML. Wyższe poziomy zapewniają lepszą kompresję kosztem wolniejszego przetwarzania.

```cpp
enum class CompressionLevel
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Nie stosuje się kompresji. Pliki są przechowywane w niezmienionej formie. |
| Level1 | 1 | Najszybsza kompresja przy najniższym współczynniku kompresji. |
| Level2 | 2 | Szybsza kompresja przy nieco lepszym współczynniku kompresji niż [CompressionLevel::Level1](./). |
| Level3 | 3 | Zapewnia lepszą kompresję niż [CompressionLevel::Level2](./) przy umiarkowanym wpływie na wydajność. |
| Level4 | 4 | Zapewnia lepszą kompresję niż [CompressionLevel::Level3](./). |
| Level5 | 5 | Zapewnia ulepszoną kompresję w porównaniu z [CompressionLevel::Level4](./) przy dodatkowym czasie przetwarzania. |
| Level6 | 6 | Standardowa kompresja, oferująca dobrą równowagę między szybkością kompresji a rozmiarem pliku. Domyślny poziom kompresji. |
| Level7 | 7 | Zapewnia wyższą kompresję niż [CompressionLevel::Level6](./) przy wolniejszym przetwarzaniu. |
| Level8 | 8 | Zapewnia wyższą kompresję niż [CompressionLevel::Level7](./). |
| Level9 | 9 | Maksymalna kompresja. Produkuje najmniejszy rozmiar pliku przy najwolniejszej prędkości przetwarzania. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)