---
title: FileVersionInfo
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt Informationen zur Dateiversion bereit. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 1
url: /de/system.diagnostics/fileversioninfo/
---
## FileVersionInfo Klasse

Stellt Informationen zur Dateiversion bereit. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class FileVersionInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Liefert das Feld für die Produktversion. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Liefert Dateiversionsinformationen; nicht implementiert. |

## Siehe auch

* Namensraum [System::Diagnostics](../)
* Bibliothek [Aspose.Slides](../../)