---
title: Rectangle class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: Speichert einen Satz von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen.
type: docs
url: /de/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle Klasse

Speichert einen Satz von vier Ganzzahlen, die den Ort und die Größe eines Rechtecks darstellen. Kompatibel mit .NET `System.Drawing.Rectangle`.

Der Rectangle-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/de/aspose.slides/rectangle/__init__/#int-int-int-int) | Erstellt ein Rechteck mit dem angegebenen Ort und der angegebenen Größe. Fließkommawerte werden zu Ganzzahlen abgeschnitten. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`x`](/slides/python-net/de/aspose.slides/rectangle/x/) | Liest die x-Koordinate der oberen linken Ecke dieses Rechtecks.<br/>            Nur lesend **int**. |
| [`y`](/slides/python-net/de/aspose.slides/rectangle/y/) | Liest die y-Koordinate der oberen linken Ecke dieses Rechtecks.<br/>            Nur lesend **int**. |
| [`width`](/slides/python-net/de/aspose.slides/rectangle/width/) | Liest die Breite dieses Rechtecks.<br/>            Nur lesend **int**. |
| [`height`](/slides/python-net/de/aspose.slides/rectangle/height/) | Liest die Höhe dieses Rechtecks.<br/>            Nur lesend **int**. |
| [`left`](/slides/python-net/de/aspose.slides/rectangle/left/) | Liest die x-Koordinate der linken Kante dieses Rechtecks. Entspricht `x`.<br/>            Nur lesend **int**. |
| [`top`](/slides/python-net/de/aspose.slides/rectangle/top/) | Liest die y-Koordinate der oberen Kante dieses Rechtecks. Entspricht `y`.<br/>            Nur lesend **int**. |
| [`right`](/slides/python-net/de/aspose.slides/rectangle/right/) | Liest die x-Koordinate, die die Summe aus `x` und `width` dieses Rechtecks ist.<br/>            Nur lesend **int**. |
| [`bottom`](/slides/python-net/de/aspose.slides/rectangle/bottom/) | Liest die y-Koordinate, die die Summe aus `y` und `height` dieses Rechtecks ist.<br/>            Nur lesend **int**. |
| [`is_empty`](/slides/python-net/de/aspose.slides/rectangle/is_empty/) | Gibt an, ob alle numerischen Eigenschaften dieses Rechtecks den Wert Null haben.<br/>            Nur lesend **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/de/aspose.slides/rectangle/contains/#int-int) | Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt. |
| [`contains(self, point)`](/slides/python-net/de/aspose.slides/rectangle/contains/#point) | Bestimmt, ob der angegebene Punkt innerhalb dieses Rechtecks liegt. |
| [`contains(self, rect)`](/slides/python-net/de/aspose.slides/rectangle/contains/#rectangle) | Bestimmt, ob der durch `rect` dargestellte rechteckige Bereich vollständig innerhalb dieses Rechtecks liegt. |


### Anmerkungen

Rechtecke werden anhand ihrer Position und Größe mit `==` verglichen und können als Dictionary-Schlüssel oder Set-Elemente verwendet werden.


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)