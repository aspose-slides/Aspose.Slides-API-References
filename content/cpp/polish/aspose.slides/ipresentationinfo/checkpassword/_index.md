---
title: CheckPassword()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Sprawdza, czy hasło jest prawidłowe dla prezentacji chronionej otwartym hasłem.
type: docs
weight: 53
url: /pl/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) metoda


Sprawdza, czy hasło jest prawidłowe dla prezentacji chronionej otwartym hasłem.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło do sprawdzenia. |

### Wartość zwracana

true, jeśli prezentacja jest chroniona otwartym hasłem i hasło jest poprawne, w przeciwnym razie false.
## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Gdy hasło jest null lub puste, metoda zwraca false. 
## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IPresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)