---
title: BulletFormat class
second_title: Aspose.Slides dla Pythona poprzez .NET Referencję API
description: 
type: docs
url: /pl/aspose.slides/bulletformat/
---
## BulletFormat klasa

Represents paragraph bullet formatting properties.

**Inheritance:**[`BulletFormat`](/slides/python-net/pl/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)

The BulletFormat type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/pl/aspose.slides/bulletformat/type/) | Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis [`BulletType`](/slides/python-net/pl/aspose.slides/bullettype). |
| [`char`](/slides/python-net/pl/aspose.slides/bulletformat/char/) | Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis **System.Char**. |
| [`font`](/slides/python-net/pl/aspose.slides/bulletformat/font/) | Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis [`IFontData`](/slides/python-net/pl/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/pl/aspose.slides/bulletformat/height/) | Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia.<br/>            Wartość float.NaN określa, że wypunktowanie dziedziczy wysokość z pierwszej części w akapicie.<br/>            Odczyt/zapis **float**. |
| [`color`](/slides/python-net/pl/aspose.slides/bulletformat/color/) | Zwraca format koloru wypunktowania akapitu bez dziedziczenia.<br/>            Tylko do odczytu [`IColorFormat`](/slides/python-net/pl/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/pl/aspose.slides/bulletformat/numbered_bullet_start_with/) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia.<br/>            Odczyt/zapis **int**. |
| [`numbered_bullet_style`](/slides/python-net/pl/aspose.slides/bulletformat/numbered_bullet_style/) | Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia.<br/>            Odczyt/zapis [`NumberedBulletStyle`](/slides/python-net/pl/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/pl/aspose.slides/bulletformat/is_bullet_hard_color/) | Określa, czy wypunktowanie ma własny kolor, czy dziedziczy go z pierwszej części akapitu.<br/>            **NullableBool.True**  jeśli wypunktowanie ma własny kolor i **NullableBool.False**  jeśli wypunktowanie<br/>            dziedziczy kolor z pierwszej części akapitu.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/pl/aspose.slides/bulletformat/is_bullet_hard_font/) | Określa, czy wypunktowanie ma własną czcionkę, czy dziedziczy ją z pierwszej części akapitu.<br/>            **NullableBool.True**  jeśli wypunktowanie ma własną czcionkę i **NullableBool.False**  jeśli wypunktowanie<br/>            dziedziczy czcionkę z pierwszej części akapitu.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/pl/aspose.slides/bulletformat/picture/) | Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia.<br/>            Tylko do odczytu [`ISlidesPicture`](/slides/python-net/pl/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/pl/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/bulletformat/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/pl/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Ustawia domyślne niezerowe przesunięcia dla efektywnego wcięcia (Indent) i lewego marginesu (MarginLeft) akapitu, gdy wypunktowanie jest włączone (tak jak PowerPoint robi to po włączeniu wypunktowań/ numeracji w akapicie). Jeśli wypunktowanie jest wyłączone, po prostu resetuje wcięcie (Indent) i lewy margines (MarginLeft) akapitu (tak jak PowerPoint robi to po wyłączeniu wypunktowań/ numeracji w akapicie). Przesunięcia wcięć są stosowane względem bieżącego kontekstu wypunktowania – IBulletFormat.Type, .NumberedBulletStyle i FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do efektywnego Indent i MarginLeft bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi). |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/bulletformat/get_effective/#) | Pobiera efektywne dane formatowania wypunktowania z zastosowanym dziedziczeniem. |


### Zobacz także
* klasa [`BulletFormat`](/slides/python-net/pl/aspose.slides/bulletformat)
* klasa [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)