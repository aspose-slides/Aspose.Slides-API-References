---
title: FileVersionInfo
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Udostępnia informacje o wersji pliku. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to spowodować błędy czasu wykonania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik System::SmartPtr i użyj tego wskaźnika, aby przekazał go do funkcji jako argument."
type: docs
weight: 1
url: /pl/system.diagnostics/fileversioninfo/
---
## FileVersionInfo klasa

Udostępnia informacje o wersji pliku. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub naruszenia asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i użyj tego wskaźnika, aby przekazać go do funkcji jako argument.

```cpp
class FileVersionInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| [String](../../system/string/) [get_ProductVersion](./get_productversion/)() const | Pobiera pole wersji produktu. |
| static [SharedPtr](../../system/sharedptr/)\<[System::Diagnostics::FileVersionInfo](./)\> [GetVersionInfo](./getversioninfo/)(const [String](../../system/string/)\&) | Pobiera informacje o wersji pliku; niezaimplementowane. |

## Zobacz także

* Przestrzeń nazw [System::Diagnostics](../)
* Biblioteka [Aspose.Slides](../../)