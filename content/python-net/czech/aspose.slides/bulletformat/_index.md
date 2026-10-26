---
title: BulletFormat class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/bulletformat/
---
## BulletFormat třída

Reprezentuje vlastnosti formátování odrážek odstavce.

**Dědičnost:**[`BulletFormat`](/slides/python-net/cs/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ BulletFormat vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides/bulletformat/type/) | Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti.<br/>            **Čtení/Zápis** [`BulletType`](/slides/python-net/cs/aspose.slides/bullettype). |
| [`char`](/slides/python-net/cs/aspose.slides/bulletformat/char/) | Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti.<br/>            **Čtení/Zápis** **System.Char**. |
| [`font`](/slides/python-net/cs/aspose.slides/bulletformat/font/) | Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti.<br/>            **Čtení/Zápis** [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/cs/aspose.slides/bulletformat/height/) | Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti.<br/>            Hodnota float.NaN určuje, že výška odrážky se dědí z první části odstavce.<br/>            **Čtení/Zápis** **float**. |
| [`color`](/slides/python-net/cs/aspose.slides/bulletformat/color/) | Vrací formát barvy odrážky odstavce bez dědičnosti.<br/>            **Pouze ke čtení** [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/cs/aspose.slides/bulletformat/numbered_bullet_start_with/) | Vrací nebo nastavuje první číslo použité pro skupinu číslovaných odrážek bez dědičnosti.<br/>            **Čtení/Zápis** **int**. |
| [`numbered_bullet_style`](/slides/python-net/cs/aspose.slides/bulletformat/numbered_bullet_style/) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti.<br/>            **Čtení/Zápis** [`NumberedBulletStyle`](/slides/python-net/cs/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/cs/aspose.slides/bulletformat/is_bullet_hard_color/) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce.<br/>            **NullableBool.True** pokud má odrážka vlastní barvu a **NullableBool.False** pokud odrážka<br/>            dědí barvu z první části odstavce.<br/>            **Čtení/Zápis** [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/cs/aspose.slides/bulletformat/is_bullet_hard_font/) | Určuje, zda má odrážka vlastní písmo nebo jej dědí z první části odstavce.<br/>            **NullableBool.True** pokud má odrážka vlastní písmo a **NullableBool.False** pokud odrážka<br/>            dědí písmo z první části odstavce.<br/>            **Čtení/Zápis** [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/cs/aspose.slides/bulletformat/picture/) | Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti.<br/>            **Pouze ke čtení** [`ISlidesPicture`](/slides/python-net/cs/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/cs/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/bulletformat/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/cs/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Nastavuje výchozí nenulové posuny pro efektivní odsazení odstavce (Indent) a levý okraj (MarginLeft), když jsou odrážky povoleny (podobně jako PowerPoint při povolení odrážek/číslování). Pokud jsou odrážky zakázány, pouze resetuje odsazení odstavce a levý okraj (podobně jako PowerPoint při zakázání odrážek/číslování). Posuny odsazení jsou aplikovány vzhledem k aktuálnímu kontextu odrážky – IBulletFormat.Type, .NumberedBulletStyle a FontHeight první části. Nenulové posuny odsazení jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (výsledné hodnoty jsou lokální). |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/bulletformat/get_effective/#) | Získává efektivní data formátování odrážky s aplikovanou dědičností. |


### Viz také
* třída [`BulletFormat`](/slides/python-net/cs/aspose.slides/bulletformat)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)