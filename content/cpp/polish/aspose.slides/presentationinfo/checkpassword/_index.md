---
title: CheckPassword()
second_title: Aspose.Slides dla C++ – referencja API
description: Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwartym.
type: docs
weight: 53
url: /pl/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) metoda


Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwartym.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło do sprawdzenia. |

### Wartość zwracana

True, jeśli prezentacja jest chroniona hasłem otwartym i hasło jest poprawne, w przeciwnym razie false.
## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Gdy hasło jest null lub puste, ta metoda zwraca false. 

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [PresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)