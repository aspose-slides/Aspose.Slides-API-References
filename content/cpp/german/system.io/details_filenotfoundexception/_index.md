---
title: Details_FileNotFoundException
second_title: Aspose.Slides für C++ API Referenz
description: "Die Ausnahme, die ausgelöst wird, wenn ein Versuch, auf eine Datei zuzugreifen, die nicht auf dem Datenträger existiert, fehlschlägt. Erstellen Sie niemals manuell Instanzen dieser Klasse. Verwenden Sie stattdessen die FileNotFoundException Klasse. Verpacken Sie niemals die FileNotFoundException Klasseninstanzen in System::SmartPtr."
type: docs
weight: 183
url: /de/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException Klasse

Die Ausnahme, die ausgelöst wird, wenn ein Versuch, auf eine Datei zuzugreifen, die nicht auf dem Datenträger existiert, fehlschlägt. Erstellen Sie niemals Instanzen dieser Klasse manuell. Verwenden Sie stattdessen die FileNotFoundException Klasse. Verpacken Sie niemals die FileNotFoundException Klasseninstanzen in [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Ermittelt den Namen der Datei, die diese Ausnahme verursacht. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Siehe auch

* Klasse [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)