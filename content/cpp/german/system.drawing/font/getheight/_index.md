---
title: GetHeight()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Zeilenabstand der Schriftart zurück, die durch das aktuelle Objekt dargestellt wird, in der aktuellen Einheit eines angegebenen Graphics-Objekts.
type: docs
weight: 14
url: /de/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) Methode


Gibt den Zeilenabstand der Schriftart zurück, die durch das aktuelle Objekt dargestellt wird, in der aktuellen Einheit eines angegebenen [Graphics](../../graphics/)-Objekts.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Ein [Graphics](../../graphics/)-Objekt, das die Maßeinheiten angibt |

## Font::GetHeight(float) Methode


Gibt die Höhe der Schriftart zurück, die durch das aktuelle Objekt dargestellt wird, wenn sie auf ein Anzeigegerät mit der angegebenen vertikalen Auflösung gezeichnet wird.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpi | **float** | Die vertikale Auflösung des Anzeigegeräts |

### Rückgabewert

Die Höhe der Schriftart in Pixeln

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Graphics](../../graphics/)
* Klasse [Font](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)