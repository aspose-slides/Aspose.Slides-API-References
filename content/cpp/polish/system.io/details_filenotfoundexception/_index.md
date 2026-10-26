---
title: Details_FileNotFoundException
second_title: Aspose.Slides dla C++ Referencja API
description: "Wyjątek zgłaszany, gdy próba dostępu do pliku, który nie istnieje na dysku, nie powiedzie się. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy FileNotFoundException zamiast tego. Nigdy nie opakowuj instancji klasy FileNotFoundException w System::SmartPtr."
type: docs
weight: 183
url: /pl/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException klasa

Wyjątek, który jest zgłaszany, gdy próba dostępu do pliku, który nie istnieje na dysku, nie powiodła się. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy FileNotFoundException zamiast tego. Nigdy nie opakowuj instancji klasy FileNotFoundException w [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | Zwraca nazwę pliku, który powoduje ten wyjątek. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## Zobacz także

* Klasa [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)