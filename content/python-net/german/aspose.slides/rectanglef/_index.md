---
title: RectangleF class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: Speichert einen Satz von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen.
type: docs
url: /de/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF Klasse

Speichert einen Satz von vier Gleitkommazahlen, die den Ort und die Größe eines Rechtecks darstellen. Kompatibel mit .NET `System.Drawing.RectangleF`.

**Vererbung:**[`RectangleF`](/slides/python-net/de/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/de/aspose.slides/rectangle)

Der Typ RectangleF stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/de/aspose.slides/rectanglef/__init__/#float-float-float-float) | Erstellt ein Rechteck mit dem angegebenen Ort und der angegebenen Größe. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`x`](/slides/python-net/de/aspose.slides/rectanglef/x/) | Liefert die x-Koordinate der oberen linken Ecke dieses Rechtecks.<br/>            Read-only **float**. |
| [`y`](/slides/python-net/de/aspose.slides/rectanglef/y/) | Liefert die y-Koordinate der oberen linken Ecke dieses Rechtecks.<br/>            Read-only **float**. |
| [`width`](/slides/python-net/de/aspose.slides/rectanglef/width/) | Liefert die Breite dieses Rechtecks.<br/>            Read-only **float**. |
| [`height`](/slides/python-net/de/aspose.slides/rectanglef/height/) | Liefert die Höhe dieses Rechtecks.<br/>            Read-only **float**. |
| [`left`](/slides/python-net/de/aspose.slides/rectanglef/left/) | Liefert die x-Koordinate der linken Kante dieses Rechtecks. Entspricht `x`.<br/>            Read-only **float**. |
| [`top`](/slides/python-net/de/aspose.slides/rectanglef/top/) | Liefert die y-Koordinate der oberen Kante dieses Rechtecks. Entspricht `y`.<br/>            Read-only **float**. |
| [`right`](/slides/python-net/de/aspose.slides/rectanglef/right/) | Liefert die x-Koordinate, die die Summe von `x` und `width` dieses Rechtecks ist.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/de/aspose.slides/rectanglef/bottom/) | Liefert die y-Koordinate, die die Summe von `y` und `height` dieses Rechtecks ist.<br/>            Read-only **float**. |
| [`is_empty`](/slides/python-net/de/aspose.slides/rectanglef/is_empty/) | Gibt an, ob alle numerischen Eigenschaften dieses Rechtecks den Wert Null haben.<br/>            Read-only **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/de/aspose.slides/rectanglef/contains/#float-float) | Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt. |
| [`contains(self, point)`](/slides/python-net/de/aspose.slides/rectanglef/contains/#pointf) | Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt. |
| [`contains(self, rect)`](/slides/python-net/de/aspose.slides/rectanglef/contains/#rectanglef) | Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks enthalten ist. |


### Bemerkungen

Rechtecke werden anhand ihrer Lage und Größe mit `==` verglichen und können als Wörterbuchschlüssel oder Mengenelemente verwendet werden.


### Siehe auch
* Klasse [`Rectangle`](/slides/python-net/de/aspose.slides/rectangle)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)