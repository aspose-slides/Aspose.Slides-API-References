---
title: CheckPassword()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppet lösenord.
type: docs
weight: 53
url: /sv/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) metod


Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppet lösenord.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet att kontrollera. |

### Returvärde

Sant om presentationen är skyddad med öppet lösenord och lösenordet är korrekt, annars falskt.
## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



När lösenordet är null eller tomt, returnerar denna metod falskt. 

## Se även

* Klass [String](../../../system/string/)
* Klass [PresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)