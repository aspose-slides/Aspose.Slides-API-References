---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/embeddinglevel/
---
## Výčtový typ EmbeddingLevel

Reprezentuje licenční práva pro vložení písma.

Typ EmbeddingLevel poskytuje následující členy:

## Pole

| Field | Description |
| :- | :- |
| INSTALLABLE | Písma s tímto nastavením označují, že je lze vložit a trvale nainstalovat na vzdáleném systému aplikací. <br/>            Uživatel vzdáleného systému získává stejné práva, povinnosti a licence pro toto písmo jako původní kupující písma, <br/>            a podléhá stejné licenční smlouvě pro koncového uživatele, autorskému právu, designovému patentu a/nebo ochranné známce jako byl původní kupující. |
| RESTRICTED | Písma, u nichž je nastaven pouze tento bit, nesmí být jakýmkoli způsobem upravována, vkládána ani vyměňována bez předchozího získání povolení od právního vlastníka. |
| PREVIEW_PRINT | Když je tento bit nastaven, písmo může být vloženo a dočasně načteno na vzdáleném systému. Dokumenty obsahující písma Preview & <br/>            Print musejí být otevřeny pouze ke čtení; nelze v nich provádět úpravy. |
| EDITABLE | Když je tento bit nastaven, písmo může být vloženo, ale musí být instalováno pouze dočasně na jiných systémech. Na rozdíl od písem Preview & <br/>            Print mohou být dokumenty obsahující písma Editable otevřeny ke čtení, úpravy jsou povoleny a změny mohou být uloženy. |
| NO_SUBSETTING | Když je tento bit nastaven, písmo nesmí být před vložením podmnoženo. Platí také ostatní omezení vložení uvedená v bitech 0-3 a 9. |
| BITMAP_ONLY | Když je tento bit nastaven, mohou být vloženy pouze bitmapy obsažené v písmu. Žádná obrysová data nemohou být vložena. Pokud ve fontu nejsou k dispozici žádné bitmapy, <br/>            je písmo považováno za nevložitelný a služby vkládání selžou. |

### Viz také
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)