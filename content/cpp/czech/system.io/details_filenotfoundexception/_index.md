---
title: Details_FileNotFoundException
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Výjimka, která je vyvolána, když se pokus o přístup k souboru, který na disku neexistuje, nezdaří. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu FileNotFoundException místo toho. Nikdy neobalujte instance třídy FileNotFoundException do System::SmartPtr."
type: docs
weight: 183
url: /cs/system.io/details_filenotfoundexception/
---
## Podrobnosti_FileNotFoundException třída

Výjimka, která je vyvolána, když se pokus o přístup k souboru, který na disku neexistuje, nezdaří. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu FileNotFoundException místo toho. Nikdy neobalujte instance třídy FileNotFoundException do [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Získá název souboru, který tuto výjimku způsobuje. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Viz také

* Třída [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)