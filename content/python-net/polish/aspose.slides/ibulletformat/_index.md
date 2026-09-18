---
title: IBulletFormat class
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/ibulletformat/
---
## IBulletFormat klasa

Reprezentuje właściwości formatowania wypunktowania akapitu.

Typ IBulletFormat udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`type`](/slides/python-net/pl/aspose.slides/ibulletformat/type/) | Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis [`BulletType`](/slides/python-net/pl/aspose.slides/bullettype). |
| [`char`](/slides/python-net/pl/aspose.slides/ibulletformat/char/) | Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis **System.Char**. |
| [`font`](/slides/python-net/pl/aspose.slides/ibulletformat/font/) | Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia.<br/>            Odczyt/zapis [`IFontData`](/slides/python-net/pl/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/pl/aspose.slides/ibulletformat/height/) | Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia.<br/>            Wartość float.NaN określa, że wypunktowanie dziedziczy wysokość z pierwszej części w akapicie.<br/>            Odczyt/zapis **float**. |
| [`color`](/slides/python-net/pl/aspose.slides/ibulletformat/color/) | Zwraca format koloru wypunktowania akapitu bez dziedziczenia.<br/>            Tylko do odczytu [`IColorFormat`](/slides/python-net/pl/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/pl/aspose.slides/ibulletformat/picture/) | Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia.<br/>            Tylko do odczytu [`ISlidesPicture`](/slides/python-net/pl/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/pl/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia.<br/>            Odczyt/zapis **int**. |
| [`numbered_bullet_style`](/slides/python-net/pl/aspose.slides/ibulletformat/numbered_bullet_style/) | Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia.<br/>            Odczyt/zapis [`IBulletFormat.numbered_bullet_style`](/slides/python-net/pl/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/pl/aspose.slides/ibulletformat/is_bullet_hard_color/) | Określa, czy wypunktowanie ma własny kolor czy dziedziczy go z pierwszej części w akapicie.<br/>            **NullableBool.True**  jeśli wypunktowanie ma własny kolor i **NullableBool.False**  jeśli wypunktowanie<br/>            dziedziczy kolor z pierwszej części w akapicie.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/pl/aspose.slides/ibulletformat/is_bullet_hard_font/) | Określa, czy wypunktowanie ma własną czcionkę czy dziedziczy ją z pierwszej części w akapicie.<br/>            **NullableBool.True**  jeśli wypunktowanie ma własną czcionkę i **NullableBool.False**  jeśli wypunktowanie<br/>            dziedziczy czcionkę z pierwszej części w akapicie.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/pl/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Ustawia domyślne niezerowe przesunięcia dla efektywnego wcięcia (Indent) i lewego marginesu (MarginLeft) akapitu, gdy wypunktowanie jest włączone (tak jak PowerPoint robi to po włączeniu wypunktowania/numeracji akapitu). Jeśli wypunktowanie jest wyłączone, przywraca wcięcie i lewy margines akapitu do wartości domyślnych (tak jak PowerPoint robi to po wyłączeniu wypunktowania/numeracji akapitu). Przesunięcia wcięć są stosowane względem bieżącego kontekstu wypunktowania – IBulletFormat.Type, .NumberedBulletStyle i FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do efektywnego wcięcia i lewego marginesu bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi). |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/ibulletformat/get_effective/#) | Pobiera efektywne dane formatowania wypunktowania z uwzględnieniem dziedziczenia. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)