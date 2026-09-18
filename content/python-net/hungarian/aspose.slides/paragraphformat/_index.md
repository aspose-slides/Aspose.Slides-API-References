---
title: ParagraphFormat class
second_title: Aspose.Slides Python számára .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/paragraphformat/
---
## ParagraphFormat osztály

Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

**Öröklődés:**[`ParagraphFormat`](/slides/python-net/hu/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)

A ParagraphFormat típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/paragraphformat/__init__/#) | Egy új [`ParagraphFormat`](/slides/python-net/hu/aspose.slides/paragraphformat) példányt inicializál. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`alignment`](/slides/python-net/hu/aspose.slides/paragraphformat/alignment/) | Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül.<br/>            Olvasás/írás [`TextAlignment`](/slides/python-net/hu/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/hu/aspose.slides/paragraphformat/space_within/) | Visszaadja vagy beállítja a sorok közti távolság mennyiségét egy bekezdésben. A pozitív érték százalékot jelent, a negatív - méretet pontban. Nem alkalmazott öröklődés.<br/>            Olvasás/írás **float**. |
| [`space_before`](/slides/python-net/hu/aspose.slides/paragraphformat/space_before/) | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy bekezdésben öröklődés nélkül.<br/>            A pozitív érték a betűméret százalékát adja meg, amely a fehér tér legyen.<br/>            A negatív érték a fehér tér méretét pontban adja meg.<br/>            Olvasás/írás **float**. |
| [`space_after`](/slides/python-net/hu/aspose.slides/paragraphformat/space_after/) | Visszaadja vagy beállítja az utolsó sor utáni térköz mennyiségét egy bekezdésben öröklődés nélkül.<br/>            A pozitív érték a betűméret százalékát adja meg, amely a fehér tér legyen.<br/>            A negatív érték a fehér tér méretét pontban adja meg.<br/>            Olvasás/írás **float**. |
| [`east_asian_line_break`](/slides/python-net/hu/aspose.slides/paragraphformat/east_asian_line_break/) | Meghatározza, hogy a kelet-ázsiai sortörés használatban van-e egy bekezdésben. Nem alkalmazott öröklődés.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/hu/aspose.slides/paragraphformat/right_to_left/) | Meghatározza, hogy jobbról balra írás használatban van-e egy bekezdésben. Nem alkalmazott öröklődés.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/hu/aspose.slides/paragraphformat/latin_line_break/) | Meghatározza, hogy a latin sortörés használatban van-e egy bekezdésben. Nem alkalmazott öröklődés.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/hu/aspose.slides/paragraphformat/hanging_punctuation/) | Meghatározza, hogy függő interpunkció használatban van-e egy bekezdésben. Nem alkalmazott öröklődés.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/hu/aspose.slides/paragraphformat/margin_left/) | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/paragraphformat/margin_right/) | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül.<br/>            Olvasás/írás **float**. |
| [`indent`](/slides/python-net/hu/aspose.slides/paragraphformat/indent/) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzását öröklődés nélkül. A függő behúzás negatív értékekkel definiálható.<br/>            Olvasás/írás **float**. |
| [`default_tab_size`](/slides/python-net/hu/aspose.slides/paragraphformat/default_tab_size/) | Visszaadja vagy beállítja az alapértelmezett tabulátor méretét öröklődés nélkül.<br/>            Olvasás/írás **float**. |
| [`tabs`](/slides/python-net/hu/aspose.slides/paragraphformat/tabs/) | Visszaadja egy bekezdés tabulátorait. Nem alkalmazott öröklődés.<br/>            Csak olvasható [`ITabCollection`](/slides/python-net/hu/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/hu/aspose.slides/paragraphformat/font_alignment/) | Visszaadja vagy beállítja a betűtípus igazítást egy bekezdésben öröklődés nélkül.<br/>            Olvasás/írás [`FontAlignment`](/slides/python-net/hu/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/hu/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/hu/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/hu/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/hu/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/paragraphformat/get_effective/#) | Visszaadja a hatékony bekezdésformázási adatokat az alkalmazott öröklődéssel. |


### Megjegyzés

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy
            értékek lekérdezésekor nem alkalmazott öröklődés, ezért a legtöbb esetben a "nem meghatározott" értékeket kapja.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterek értékeinek lekéréséhez a [`ParagraphFormat.get_effective`](/slides/python-net/hu/aspose.slides/paragraphformat/get_effective) metódust kell használnia,
            amely egy [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata) példányt ad vissza.

### Lásd még
* osztály [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata)
* osztály [`ParagraphFormat`](/slides/python-net/hu/aspose.slides/paragraphformat)
* osztály [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)