---
title: IBulletFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ibulletformat/
---
## IBulletFormat classe

Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.

Il tipo IBulletFormat espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides/ibulletformat/type/) | Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura [`BulletType`](/slides/python-net/it/aspose.slides/bullettype). |
| [`char`](/slides/python-net/it/aspose.slides/ibulletformat/char/) | Restituisce o imposta il carattere di punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura **System.Char**. |
| [`font`](/slides/python-net/it/aspose.slides/ibulletformat/font/) | Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/it/aspose.slides/ibulletformat/height/) | Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà.<br/>            Il valore float.NaN determina che il punto elenco erediti l'altezza dalla prima porzione del paragrafo.<br/>            Lettura/Scrittura **float**. |
| [`color`](/slides/python-net/it/aspose.slides/ibulletformat/color/) | Restituisce il formato colore di un punto elenco di un paragrafo senza ereditarietà.<br/>            Solo lettura [`IColorFormat`](/slides/python-net/it/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/it/aspose.slides/ibulletformat/picture/) | Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà.<br/>            Solo lettura [`ISlidesPicture`](/slides/python-net/it/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/it/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Restituisce o imposta il primo numero utilizzato per il gruppo di punti elenco numerati senza ereditarietà.<br/>            Lettura/Scrittura **int**. |
| [`numbered_bullet_style`](/slides/python-net/it/aspose.slides/ibulletformat/numbered_bullet_style/) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà.<br/>            Lettura/Scrittura [`IBulletFormat.numbered_bullet_style`](/slides/python-net/it/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/it/aspose.slides/ibulletformat/is_bullet_hard_color/) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo.<br/>            **NullableBool.True**  se il punto elenco ha un colore proprio e **NullableBool.False**  se il punto elenco<br/>            eredita il colore dalla prima porzione del paragrafo.<br/>            Lettura/Scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/it/aspose.slides/ibulletformat/is_bullet_hard_font/) | Determina se il punto elenco ha un carattere proprio o lo eredita dalla prima porzione del paragrafo.<br/>            **NullableBool.True**  se il punto elenco ha un carattere proprio e **NullableBool.False**  se il punto elenco<br/>            eredita il carattere dalla prima porzione del paragrafo.<br/>            Lettura/Scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |

## Metodi

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/it/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Imposta gli spostamenti predefiniti diversi da zero per l'Indentazione e il MarginLeft efficaci del paragrafo quando i punti elenco sono abilitati (come fa PowerPoint se si attivano i punti elenco/numerazione del paragrafo). Se i punti elenco sono disabilitati, resetta semplicemente l'Indentazione e il MarginLeft del paragrafo (come fa PowerPoint se si disattivano i punti elenco/numerazione). Gli spostamenti di indentazione sono applicati in base al contesto corrente del punto elenco – IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione diversi da zero sono applicati all'Indentazione e al MarginLeft effettivi del paragrafo corrente (rendendo i valori risultanti valori locali). |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/ibulletformat/get_effective/#) | Ottiene i dati di formattazione del punto elenco effettivi con l'ereditarietà applicata. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)