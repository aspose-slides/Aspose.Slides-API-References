---
title: IParagraphFormat class
second_title: Aspose.Slides Python számára .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/iparagraphformat/
---
## IParagraphFormat osztály

Ez az osztály a bekezdés formázási tulajdonságait tartalmazza. A [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata)-től eltérően ennek az osztálynak az összes tulajdonsága írható.

Az IParagraphFormat típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`bullet`](/slides/python-net/hu/aspose.slides/iparagraphformat/bullet/) | Visszaadja a bekezdés felsorolás formátumát.<br/>            Csak olvasható [`IBulletFormat`](/slides/python-net/hu/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/hu/aspose.slides/iparagraphformat/depth/) | Visszaadja vagy beállítja a bekezdés mélységét.<br/>            A 0 érték undefined értéket jelent.<br/>            Olvasás/írás **int**. |
| [`alignment`](/slides/python-net/hu/aspose.slides/iparagraphformat/alignment/) | Visszaadja vagy beállítja a szöveg igazítását egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Olvasás/írás [`TextAlignment`](/slides/python-net/hu/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/hu/aspose.slides/iparagraphformat/space_within/) | Visszaadja vagy beállítja a base vonalak közötti távolság mennyiségét egy bekezdésben. Pozitív érték esetén százalékot jelent, negatív – pontméretet. Nem alkalmaz öröklődést.<br/>            Olvasás/írás **float**. |
| [`space_before`](/slides/python-net/hu/aspose.slides/iparagraphformat/space_before/) | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Pozitív érték esetén a betűméret százalékában adja meg a fehér helyet.<br/>            Negatív érték esetén pontméretben adja meg a fehér helyet.<br/>            Olvasás/írás **float**. |
| [`space_after`](/slides/python-net/hu/aspose.slides/iparagraphformat/space_after/) | Visszaadja vagy beállítja az utolsó sor utáni térköz mennyiségét egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Pozitív érték esetén a betűméret százalékában adja meg a fehér helyet.<br/>            Negatív érték esetén pontméretben adja meg a fehér helyet.<br/>            Olvasás/írás **float**. |
| [`east_asian_line_break`](/slides/python-net/hu/aspose.slides/iparagraphformat/east_asian_line_break/) | Megállapítja, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nem alkalmaz öröklődést.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/hu/aspose.slides/iparagraphformat/right_to_left/) | Megállapítja, hogy jobbról balra írásra van-e szükség egy bekezdésben. Nem alkalmaz öröklődést.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/hu/aspose.slides/iparagraphformat/latin_line_break/) | Megállapítja, hogy a latin sortörés használatban van-e egy bekezdésben. Nem alkalmaz öröklődést.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/hu/aspose.slides/iparagraphformat/hanging_punctuation/) | Megállapítja, hogy függő írásjelek használata aktív-e egy bekezdésben. Nem alkalmaz öröklődést.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/hu/aspose.slides/iparagraphformat/margin_left/) | Visszaadja vagy beállítja a bal margót egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/iparagraphformat/margin_right/) | Visszaadja vagy beállítja a jobb margót egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Olvasás/írás **float**. |
| [`indent`](/slides/python-net/hu/aspose.slides/iparagraphformat/indent/) | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel definiálható.<br/>            Olvasás/írás **float**. |
| [`default_tab_size`](/slides/python-net/hu/aspose.slides/iparagraphformat/default_tab_size/) | Visszaadja vagy beállítja az alapértelmezett tabulálási méretet öröklődés nélkül.<br/>            Olvasás/írás **float**. |
| [`tabs`](/slides/python-net/hu/aspose.slides/iparagraphformat/tabs/) | Visszaadja a bekezdés tabulációit. Nem alkalmaz öröklődést.<br/>            Csak olvasható [`ITabCollection`](/slides/python-net/hu/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/hu/aspose.slides/iparagraphformat/font_alignment/) | Visszaadja vagy beállítja a betűtípus igazítását egy olyan bekezdésben, amelyre nem vonatkozik öröklődés.<br/>            Olvasás/írás [`FontAlignment`](/slides/python-net/hu/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/hu/aspose.slides/iparagraphformat/default_portion_format/) | Visszaadja a bekezdés alapértelmezett részformátumát. Nem alkalmaz öröklődést.<br/>            Csak olvasható [`IPortionFormat`](/slides/python-net/hu/aspose.slides/iportionformat). |

## Metódusok

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/iparagraphformat/get_effective/#) | Lekéri a hatékony bekezdésformázási adatokat az alkalmazott öröklődéssel. |

### Megjegyzések

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérdezésekor nem alkalmazzák az öröklődést, ezért a legtöbb esetben olyan értékekkel találkozik, amelyek "undefined"-et jelentenek.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`IParagraphFormat.get_effective`](/slides/python-net/hu/aspose.slides/iparagraphformat/get_effective) metódust kell használni, amely egy [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata) példányt ad vissza.

### Lásd még
* osztály [`IParagraphFormatEffectiveData`](/slides/python-net/hu/aspose.slides/iparagraphformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)