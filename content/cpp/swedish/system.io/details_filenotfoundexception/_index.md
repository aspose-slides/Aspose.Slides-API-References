---
title: Details_FileNotFoundException
second_title: Aspose.Slides för C++ API-referens
description: "Undantaget som kastas när ett försök att komma åt en fil som inte finns på disken misslyckas. Skapa aldrig instanser av denna klass manuellt. Använd klassen FileNotFoundException istället. Packa aldrig in instanser av klassen FileNotFoundException i System::SmartPtr."
type: docs
weight: 183
url: /sv/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException klass

Undantaget som kastas när ett försök att komma åt en fil som inte finns på disken misslyckas. Skapa aldrig instanser av denna klass manuellt. Använd klassen FileNotFoundException istället. Packa aldrig in instanser av klassen FileNotFoundException i [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Hämtar namnet på filen som orsakar detta undantag. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Se även

* Klass [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Namnrymd [System::IO](../)
* Bibliotek [Aspose.Slides](../../)