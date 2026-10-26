---
title: BulletFormat class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/bulletformat/
---
## BulletFormat Klasse

Stellt die Aufzählungsformatierungseigenschaften eines Absatzes dar.

**Vererbung:**[`BulletFormat`](/slides/python-net/de/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)

Der Typ BulletFormat stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/de/aspose.slides/bulletformat/type/) | Gibt den Aufzählungstyp eines Absatzes ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`BulletType`](/slides/python-net/de/aspose.slides/bullettype). |
| [`char`](/slides/python-net/de/aspose.slides/bulletformat/char/) | Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt es fest.<br/>            Lesen/Schreiben **System.Char**. |
| [`font`](/slides/python-net/de/aspose.slides/bulletformat/font/) | Gibt die Aufzählungsschriftart eines Absatzes ohne Vererbung zurück oder legt sie fest.<br/>            Lesen/Schreiben [`IFontData`](/slides/python-net/de/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/de/aspose.slides/bulletformat/height/) | Gibt die Höhe der Aufzählung eines Absatzes ohne Vererbung zurück oder legt sie fest.<br/>            Der Wert float.NaN bestimmt, dass die Aufzählung die Höhe vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben **float**. |
| [`color`](/slides/python-net/de/aspose.slides/bulletformat/color/) | Gibt das Farbformat einer Aufzählung eines Absatzes ohne Vererbung zurück.<br/>            Nur-Lesen [`IColorFormat`](/slides/python-net/de/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/de/aspose.slides/bulletformat/numbered_bullet_start_with/) | Gibt die erste Nummer zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungen ohne Vererbung verwendet wird.<br/>            Lesen/Schreiben **int**. |
| [`numbered_bullet_style`](/slides/python-net/de/aspose.slides/bulletformat/numbered_bullet_style/) | Gibt den Stil einer nummerierten Aufzählung ohne Vererbung zurück oder legt ihn fest.<br/>            Lesen/Schreiben [`NumberedBulletStyle`](/slides/python-net/de/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/de/aspose.slides/bulletformat/is_bullet_hard_color/) | Bestimmt, ob die Aufzählung eine eigene Farbe hat oder sie vom ersten Abschnitt im Absatz erbt.<br/>            **NullableBool.True**  wenn die Aufzählung eine eigene Farbe hat und **NullableBool.False**  wenn die Aufzählung<br/>            die Farbe vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/de/aspose.slides/bulletformat/is_bullet_hard_font/) | Bestimmt, ob die Aufzählung eine eigene Schriftart hat oder sie vom ersten Abschnitt im Absatz erbt.<br/>            **NullableBool.True**  wenn die Aufzählung eine eigene Schriftart hat und **NullableBool.False**  wenn die Aufzählung<br/>            die Schriftart vom ersten Abschnitt im Absatz erbt.<br/>            Lesen/Schreiben [`NullableBool`](/slides/python-net/de/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/de/aspose.slides/bulletformat/picture/) | Gibt das Bild zurück, das als Aufzählung in einem Absatz ohne Vererbung verwendet wird.<br/>            Nur-Lesen [`ISlidesPicture`](/slides/python-net/de/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/de/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/bulletformat/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/de/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | Setzt die Standard-Verschiebungen (ungleich Null) für den effektiven Absatz-Indent und MarginLeft, wenn Aufzählungen aktiviert sind (wie PowerPoint es tut, wenn Absatz-Aufzählungen/Nummerierungen aktiviert werden). Ist Aufzählung deaktiviert, werden nur Indent und MarginLeft des Absatzes zurückgesetzt (wie PowerPoint es tut, wenn Absatz-Aufzählungen/Nummerierungen deaktiviert werden). Einrückungs-Verschiebungen werden in Bezug auf den aktuellen Aufzählungskontext – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Abschnitts – angewendet. Ungleich-null-Einrückungs-Verschiebungen werden auf den effektiven Indent und MarginLeft des aktuellen Absatzes angewendet (damit die Ergebniswerte lokale Werte werden). |
| [`get_effective(self)`](/slides/python-net/de/aspose.slides/bulletformat/get_effective/#) | Ermittelt die effektiven Aufzählungsformatierungsdaten mit angewandter Vererbung. |

### Siehe auch
* Klasse [`BulletFormat`](/slides/python-net/de/aspose.slides/bulletformat)
* Klasse [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)