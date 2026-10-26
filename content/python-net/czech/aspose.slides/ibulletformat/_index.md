---
title: IBulletFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ibulletformat/
---
## IBulletFormat třída

Representuje vlastnosti formátování odrážek odstavce.

Typ IBulletFormat vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/cs/aspose.slides/ibulletformat/type/) | Vrací nebo nastavuje typ odrážky odstavce bez dědičnosti.<br/>            Číst/Zapisovat [`BulletType`](/slides/python-net/cs/aspose.slides/bullettype). |
| [`char`](/slides/python-net/cs/aspose.slides/ibulletformat/char/) | Vrací nebo nastavuje znak odrážky odstavce bez dědičnosti.<br/>            Číst/Zapisovat **System.Char**. |
| [`font`](/slides/python-net/cs/aspose.slides/ibulletformat/font/) | Vrací nebo nastavuje písmo odrážky odstavce bez dědičnosti.<br/>            Číst/Zapisovat [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/cs/aspose.slides/ibulletformat/height/) | Vrací nebo nastavuje výšku odrážky odstavce bez dědičnosti.<br/>            Hodnota float.NaN určuje, že odrážka dědí výšku z první části odstavce.<br/>            Číst/Zapisovat **float**. |
| [`color`](/slides/python-net/cs/aspose.slides/ibulletformat/color/) | Vrací formát barvy odrážky odstavce bez dědičnosti.<br/>            Pouze ke čtení [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/cs/aspose.slides/ibulletformat/picture/) | Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti.<br/>            Pouze ke čtení [`ISlidesPicture`](/slides/python-net/cs/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/cs/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Vrací nebo nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti.<br/>            Číst/Zapisovat **int**. |
| [`numbered_bullet_style`](/slides/python-net/cs/aspose.slides/ibulletformat/numbered_bullet_style/) | Vrací nebo nastavuje styl číslované odrážky bez dědičnosti.<br/>            Číst/Zapisovat [`IBulletFormat.numbered_bullet_style`](/slides/python-net/cs/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/cs/aspose.slides/ibulletformat/is_bullet_hard_color/) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce.<br/>            **NullableBool.True** pokud má odrážka vlastní barvu a **NullableBool.False** pokud odrážka dědí barvu z první části odstavce.<br/>            Číst/Zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/cs/aspose.slides/ibulletformat/is_bullet_hard_font/) | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce.<br/>            **NullableBool.True** pokud má odrážka vlastní písmo a **NullableBool.False** pokud odrážka dědí písmo z první části odstavce.<br/>            Číst/Zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |

## Metody

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/cs/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Nastavuje výchozí ne-nulové posuny pro efektivní Indent a MarginLeft odstavce, když jsou odrážky povoleny (podobně jako PowerPoint při povolení odrážek/číslování). Pokud jsou odrážky zakázány, pouze resetuje Indent a MarginLeft odstavce (podobně jako PowerPoint při zakázání odrážek/číslování). Posuny odsazení jsou aplikovány vzhledem k aktuálnímu kontextu odrážky – IBulletFormat.Type, .NumberedBulletStyle a FontHeight první části. Ne-nulové posuny jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (aby výsledné hodnoty byly lokální). |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/ibulletformat/get_effective/#) | Získává efektivní data formátování odrážky s aplikovanou dědičností. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)