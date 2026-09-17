---
title: IBulletFormat class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ibulletformat/
---
## IBulletFormat Klasse

Stellt die Formatierungseigenschaften von Aufzählungszeichen für Absätze dar.

Der IBulletFormat-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides/ibulletformat/type/) | Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`BulletType`](/slides/python-net/de/aspose.slides/bullettype). |
| [`char`](/slides/python-net/de/aspose.slides/ibulletformat/char/) | Gibt das Aufzählungszeichen-Zeichen eines Absatzes ohne Vererbung zurück oder legt es fest.<br/>            Lesen/Schreiben **System.Char**. |
| [`font`](/slides/python-net/de/aspose.slides/ibulletformat/font/) | Gibt die Aufzählungszeichen-Schriftart eines Absatzes ohne Vererbung zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/de/aspose.slides/ibulletformat/height/) | Gibt die Aufzählungszeichen-Höhe eines Absatzes ohne Vererbung zurück oder legt sie fest.<br/>            Der Wert float.NaN bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben **float**. |
| [`color`](/slides/python-net/de/aspose.slides/ibulletformat/color/) | Gibt das Farbformat eines Aufzählungszeichens eines Absatzes ohne Vererbung zurück.<br/>            Nur lesen [`IColorFormat`](/slides/python-net/de/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/de/aspose.slides/ibulletformat/picture/) | Gibt das Bild zurück, das als Aufzählungszeichen in einem Absatz ohne Vererbung verwendet wird.<br/>            Nur lesen [`ISlidesPicture`](/slides/python-net/de/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/de/aspose.slides/ibulletformat/numbered_bullet_start_with/) | Gibt die erste Nummer zurück, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird, oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`numbered_bullet_style`](/slides/python-net/de/aspose.slides/ibulletformat/numbered_bullet_style/) | Gibt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`IBulletFormat.numbered_bullet_style`](/slides/python-net/de/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/de/aspose.slides/ibulletformat/is_bullet_hard_color/) | Bestimmt, ob das Aufzählungszeichen eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt.<br/>            **NullableBool.True**  wenn das Aufzählungszeichen eine eigene Farbe hat und **NullableBool.False**  wenn das Aufzählungszeichen die Farbe vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/de/aspose.slides/ibulletformat/is_bullet_hard_font/) | Bestimmt, ob das Aufzählungszeichen eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt.<br/>            **NullableBool.True**  wenn das Aufzählungszeichen eine eigene Schriftart hat und **NullableBool.False**  wenn das Aufzählungszeichen die Schriftart vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |

## Methoden

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/de/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | Setzt Standardverschiebungen ungleich Null für den effektiven Absatz-Einzug (Indent) und den linken Rand (MarginLeft), wenn Aufzählungszeichen aktiviert sind (wie PowerPoint es macht, wenn Absatz-Aufzählungszeichen/Nummerierung aktiviert werden). Wenn Aufzählungszeichen deaktiviert sind, werden lediglich der Absatz-Einzug und der linke Rand zurückgesetzt (wie PowerPoint es macht, wenn Absatz-Aufzählungszeichen/Nummerierung deaktiviert werden). Einzugsverschiebungen werden im Hinblick auf den aktuellen Aufzählungskontext angewendet – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts. Verschiebungen ungleich Null werden auf den effektiven Einzug und den linken Rand des aktuellen Absatzes angewendet (machen die Ergebniswerte zu lokalen Werten). |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/ibulletformat/get_effective/#) | Ruft die wirksamen Aufzählungsformatierungsdaten mit angewandter Vererbung ab. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)