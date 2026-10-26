---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/colortransformoperation/
---
## ColorTransformOperation Aufzählung

Definiert Farbtransformationsoperation.

Der Typ ColorTransformOperation stellt die folgenden Mitglieder bereit:

## Felder

| Feld | Beschreibung |
| :- | :- |
| TINT | Färbt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Weiß). |
| SHADE | Verdunkelt die Farbe. Der Parameter liegt im Bereich zwischen 0 (Originalfarbe) und 1 (Schwarz). |
| COMPLEMENT | Ändert die Farbe in eine RGB-Komplementärfarbe.<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | Ändert die Farbe in eine invertierte Farbe.<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | Ändert die Farbe in ein Graustufenbild mit gleicher Helligkeit. Parameter wird ignoriert. |
| SET_ALPHA | Definiert eine Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen 0 (transparent) und 1 (undurchsichtig). |
| ADD_ALPHA | Addiert den Wert eines Parameters zur Alpha-Komponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_ALPHA | Multipliziert die Alpha-Komponente mit dem Wert eines Parameters. |
| SET_HUE | Ändert die Farbtonkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 360. |
| ADD_HUE | Addiert den Wert eines Parameters zur Farbtonkomponente der Farbe. Der Parameter liegt im Bereich zwischen -360 und 360. |
| MULTIPLY_HUE | Multipliziert die Farbtonkomponente mit dem Wert eines Parameters. |
| SET_SATURATION | Ändert die Sättigungskomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| ADD_SATURATION | Addiert den Wert eines Parameters zur Sättigungskomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_SATURATION | Multipliziert die Sättigungskomponente mit dem Wert eines Parameters. |
| SET_LUMINANCE | Ändert die Leuchtkraftkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| ADD_LUMINANCE | Addiert den Wert eines Parameters zur Leuchtkraftkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_LUMINANCE | Multipliziert die Leuchtkraftkomponente mit dem Wert eines Parameters. |
| SET_RED | Ändert die Rotkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| ADD_RED | Addiert den Wert eines Parameters zur Rotkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_RED | Multipliziert die Rotkomponente mit einem Parameter. |
| SET_GREEN | Ändert die Grünkomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 1. |
| ADD_GREEN | Addiert einen Parameter zur Grünkomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_GREEN | Multipliziert die Grünkomponente mit dem Wert eines Parameters. |
| SET_BLUE | Ändert die Blaukomponente der Farbe auf den Wert eines Parameters. Der Parameter liegt im Bereich zwischen 0 und 360. |
| ADD_BLUE | Addiert den Wert eines Parameters zur Blaukomponente der Farbe. Der Parameter liegt im Bereich zwischen -1 und 1. |
| MULTIPLY_BLUE | Multipliziert die Blaukomponente mit dem Wert eines Parameters. |
| GAMMA | Gammakorrektur. Parameter wird ignoriert. |
| INVERSE_GAMMA | Inverse Gammakorrektur. Parameter wird ignoriert. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)