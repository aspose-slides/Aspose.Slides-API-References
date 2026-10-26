---
title: BulletFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/bulletformat/
---
## BulletFormat classe

Rappresenta le proprietà di formattazione dei punti elenco del paragrafo.

**Ereditarietà:**[`BulletFormat`](/slides/python-net/it/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)

Il tipo BulletFormat espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`type`](/slides/python-net/it/aspose.slides/bulletformat/type/) | Restituisce o imposta il tipo di punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura [`BulletType`](/slides/python-net/it/aspose.slides/bullettype). |
| [`char`](/slides/python-net/it/aspose.slides/bulletformat/char/) | Restituisce o imposta il carattere del punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura **System.Char**. |
| [`font`](/slides/python-net/it/aspose.slides/bulletformat/font/) | Restituisce o imposta il font del punto elenco di un paragrafo senza ereditarietà.<br/>            Lettura/Scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/it/aspose.slides/bulletformat/height/) | Restituisce o imposta l'altezza del punto elenco di un paragrafo senza ereditarietà.<br/>            Il valore float.NaN determina che il punto elenco eredita l'altezza dalla prima porzione nel paragrafo.<br/>            Lettura/Scrittura **float**. |
| [`color`](/slides/python-net/it/aspose.slides/bulletformat/color/) | Restituisce il formato colore di un punto elenco di un paragrafo senza ereditarietà.<br/>            Solo lettura [`IColorFormat`](/slides/python-net/it/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/it/aspose.slides/bulletformat/numbered_bullet_start_with/) | Restituisce o imposta il primo numero usato per il gruppo di punti elenco numerati senza ereditarietà.<br/>            Lettura/Scrittura **int**. |
| [`numbered_bullet_style`](/slides/python-net/it/aspose.slides/bulletformat/numbered_bullet_style/) | Restituisce o imposta lo stile di un punto elenco numerato senza ereditarietà.<br/>            Lettura/Scrittura [`NumberedBulletStyle`](/slides/python-net/it/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/it/aspose.slides/bulletformat/is_bullet_hard_color/) | Determina se il punto elenco ha un colore proprio o lo eredita dalla prima porzione del paragrafo.<br/>            **NullableBool.True**  se il punto elenco ha un colore proprio e **NullableBool.False**  se il punto elenco<br/>            eredita il colore dalla prima porzione del paragrafo.<br/>            Lettura/Scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/it/aspose.slides/bulletformat/is_bullet_hard_font/) | Determina se il punto elenco ha un font proprio o lo eredita dalla prima porzione del paragrafo.<br/>            **NullableBool.True**  se il punto elenco ha un font proprio e **NullableBool.False**  se il punto elenco<br/>            eredita il font dalla prima porzione del paragrafo.<br/>            Lettura/Scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/it/aspose.slides/bulletformat/picture/) | Restituisce l'immagine usata come punto elenco in un paragrafo senza ereditarietà.<br/>            Solo lettura [`ISlidesPicture`](/slides/python-net/it/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/it/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/bulletformat/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/it/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Imposta gli spostamenti predefiniti diversi da zero per l'Indent e il MarginLeft efficaci del paragrafo quando i bullet sono abilitati (come fa PowerPoint se si attiva la numerazione/punti elenco del paragrafo). Se i bullet sono disabilitati, ripristina semplicemente l'Indent e il MarginLeft del paragrafo (come fa PowerPoint se si disabilita la numerazione/punti elenco del paragrafo). Gli spostamenti di indentazione sono applicati in base al contesto corrente del bullet - IBulletFormat.Type, .NumberedBulletStyle e FontHeight della prima porzione. Gli spostamenti di indentazione diversi da zero sono applicati a Indent e MarginLeft efficaci del paragrafo corrente (rendendo i valori risultanti valori locali). |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/bulletformat/get_effective/#) | Ottiene i dati di formattazione efficaci del bullet con l'ereditarietà applicata. |

### Vedi anche
* classe [`BulletFormat`](/slides/python-net/it/aspose.slides/bulletformat)
* classe [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)