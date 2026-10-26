---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enumeration

Representerar licensrättigheter för inbäddning av typsnittet.

EmbeddingLevel-typen exponerar följande medlemmar:

## Fält

| Fält | Beskrivning |
| :- | :- |
| INSTALLABLE | Typsnitt med denna inställning indikerar att de kan bäddas in och permanent installeras på det fjärranslutna systemet av en applikation. <br/>            Användaren av det fjärranslutna systemet får samma rättigheter, skyldigheter och licenser för det typsnittet som den ursprungliga köparen av typsnittet, <br/>            och är föremål för samma slutanvändarlicensavtal, upphovsrätt, designpatent och/eller varumärke som den ursprungliga köparen. |
| RESTRICTED | Typsnitt som endast har denna bit satt får inte modifieras, bäddas in eller utbytas på något sätt utan att först erhålla tillstånd från den rättsliga ägaren. |
| PREVIEW_PRINT | När denna bit är satt kan typsnittet bäddas in och tillfälligt laddas på det fjärranslutna systemet. Dokument som innehåller Preview & <br/>            Print-typsnitt måste öppnas i "read-only"; inga redigeringar kan göras i dokumentet. |
| EDITABLE | När denna bit är satt kan typsnittet bäddas in men får endast installeras tillfälligt på andra system. Till skillnad från Preview & <br/>            Print-typsnitt kan dokument som innehåller Editable-typsnitt öppnas för läsning, redigering är tillåten och ändringar kan sparas. |
| NO_SUBSETTING | När denna bit är satt får typsnittet inte subsets innan inbäddning. Andra inbäddningsrestriktioner som specificeras i bitarna 0-3 och 9 gäller också. |
| BITMAP_ONLY | När denna bit är satt får endast bitmapar som finns i typsnittet bäddas in. Ingen konturdata får bäddas in. Om det inte finns några bitmapar tillgängliga i typsnittet, <br/>            anses typsnittet vara icke-inbäddningsbart och inbäddningstjänsterna kommer att misslyckas. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)