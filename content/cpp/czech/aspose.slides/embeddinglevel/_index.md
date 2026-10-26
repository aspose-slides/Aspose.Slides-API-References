---
title: EmbeddingLevel
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Representuje licenční práva pro vkládání písma.
type: docs
weight: 5786
url: /cs/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Representuje licenční práva pro vkládání písma.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) s tímto nastavením naznačuje, že mohou být vloženy a trvale nainstalovány na vzdáleném systému aplikací. Uživatel vzdáleného systému získá stejné práva, povinnosti a licence pro toto písmo jako původní kupující písma a podléhá stejné koncovému licenčnímu ujednání, autorskému právu, designovému patentu a/nebo ochranné známce jako původní kupující. |
| Restricted | 2 | [Fonts](../fonts/) které mají nastaven pouze tento bit, nesmí být upravovány, vkládány ani vyměňovány žádným způsobem bez předchozího získání povolení od právního vlastníka. |
| PreviewPrint | 4 | Když je tento bit nastaven, písmo může být vloženo a dočasně načteno na vzdáleném systému. Dokumenty obsahující Preview & Print písma musí být otevřeny \"pouze ke čtení\"; ke změnám dokumentu nelze přistoupit. |
| Editable | 8 | Když je tento bit nastaven, písmo může být vloženo, ale musí být nainstalováno pouze dočasně na jiných systémech. Na rozdíl od písem Preview & Print mohou být dokumenty obsahující Editable písma otevřeny pro čtení, úpravy jsou povoleny a změny lze uložit. |
| NoSubsetting | 256 | Když je tento bit nastaven, písmo nesmí být před vložením podmnoženo. Platí také další omezení vložení uvedená v bitech 0-3 a 9. |
| BitmapOnly | 512 | Když je tento bit nastaven, mohou být vloženy pouze bitmapy obsažené v písmu. Žádná data obrysu nesmí být vložena. Pokud nejsou v písmu k dispozici žádné bitmapy, písmo se považuje za nevložitelný a služby vložení selžou. |

## Viz také

* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)