---
title: ColorTranslator
second_title: Aspose.Slides für C++ API-Referenz
description: "Führt Farbübersetzungen durch. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Verpacken Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 66
url: /de/system.drawing/colortranslator/
---
## ColorTranslator Klasse

Führt Farbübersetzungen durch. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion erstellt werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ColorTranslator
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Konvertiert die angegebene HTML-Farbrepräsentation in das entsprechende [Color](../color/)-Objekt. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Konvertiert die angegebene [Windows](../../system.windows/)-Farbe in das entsprechende [Color](../color/)-Objekt. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Konvertiert das angegebene [Color](../color/)-Objekt in die Zeichenkettenrepräsentation der entsprechenden HTML-Farbe. |

## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)