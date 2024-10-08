---
title: BulletFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert Formatierungseigenschaften für Absatzaufzählungszeichen.
type: docs
weight: 970
url: /de/aspose.slides/bulletformat/
---
## BulletFormat class

Repräsentiert Formatierungseigenschaften für Absatzaufzählungszeichen.

```csharp
public class BulletFormat : PVIObject, IBulletFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../ipresentationcomponent) . |
| [Char](../../aspose.slides/bulletformat/char) { get; set; } | Gibt das Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder setzt es. Lesen/SchreibenChar . |
| [Color](../../aspose.slides/bulletformat/color) { get; } | Gibt das Farbformat eines Aufzählungszeichens eines Absatzes ohne Vererbung zurück. Schreibgeschützt[`IColorFormat`](../icolorformat) . |
| [Font](../../aspose.slides/bulletformat/font) { get; set; } | Gibt die Schriftart für Aufzählungszeichen eines Absatzes ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [Height](../../aspose.slides/bulletformat/height) { get; set; } | Gibt die Höhe des Aufzählungszeichens eines Absatzes ohne Vererbung zurück oder legt sie fest. Der Wert float.NaN bestimmt, dass das Aufzählungszeichen die Höhe vom ersten Teil des Absatzes erbt. Lesen/SchreibenSingle . |
| [IsBulletHardColor](../../aspose.slides/bulletformat/isbullethardcolor) { get; set; } | Legt fest, ob das Aufzählungszeichen eine eigene Farbe hat oder diese vom ersten Teil des Absatzes erbt.  **NullableBool.True** wenn Kugel eigene Farbe hat und **NullableBool.False** if bullet erbt die Farbe vom ersten Teil des Absatzes. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [IsBulletHardFont](../../aspose.slides/bulletformat/isbullethardfont) { get; set; } | Legt fest, ob das Aufzählungszeichen eine eigene Schriftart hat oder diese vom ersten Teil des Absatzes erbt.  **NullableBool.True** wenn Aufzählungszeichen eigene Schriftart hat und **NullableBool.False**if bullet erbt die Schriftart vom ersten Teil des Absatzes. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [NumberedBulletStartWith](../../aspose.slides/bulletformat/numberedbulletstartwith) { get; set; } | Gibt die erste Zahl zurück oder legt sie fest, die für eine Gruppe nummerierter Aufzählungszeichen ohne Vererbung verwendet wird. Lesen/SchreibenInt16 . |
| [NumberedBulletStyle](../../aspose.slides/bulletformat/numberedbulletstyle) { get; set; } | Gibt den Stil eines nummerierten Aufzählungszeichens ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben[`NumberedBulletStyle`](../numberedbulletstyle) . |
| [Picture](../../aspose.slides/bulletformat/picture) { get; } | Gibt das Bild zurück, das als Aufzählungszeichen in einem Absatz ohne Vererbung verwendet wird. Schreibgeschützt[`ISlidesPicture`](../islidespicture) . |
| [Type](../../aspose.slides/bulletformat/type) { get; set; } | Gibt den Aufzählungszeichentyp eines Absatzes ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben[`BulletType`](../bullettype) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ApplyDefaultParagraphIndentsShifts](../../aspose.slides/bulletformat/applydefaultparagraphindentsshifts)() | Legt standardmäßige Nicht-Null-Verschiebungen für den effektiven Absatzeinzug und MarginLeft fest, wenn Aufzählungszeichen aktiviert sind (wie es PowerPoint tut, wenn Absatzaufzählungszeichen/Nummerierung darin aktiviert sind). Wenn Aufzählungszeichen deaktiviert sind, setzen Sie einfach Absatzeinzug und MarginLeft zurück (wie PowerPoint es tut, wenn Absatzaufzählungszeichen/Nummerierung darin deaktiviert sind). Verschiebungen von Einzügen werden in Bezug auf den aktuellen Aufzählungskontext angewendet – IBulletFormat.Type, .NumberedBulletStyle und FontHeight des ersten Teils. Verschiebungen von Einzügen ungleich Null werden auf den effektiven Einzug und den linken Rand des aktuellen Absatzes angewendet (Ergebniswerte werden zu lokalen Werten). |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| [GetEffective](../../aspose.slides/bulletformat/geteffective)() | Ruft effektive Aufzählungsformatierungsdaten mit angewendeter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt Hash-Code zurück. |

### Siehe auch

* class [PVIObject](../pviobject)
* interface [IBulletFormat](../ibulletformat)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
