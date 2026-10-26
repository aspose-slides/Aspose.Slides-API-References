---
title: CheckPassword()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett lösenord är korrekt för en presentation som är skyddad med öppet lösenord.
type: docs
weight: 53
url: /sv/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) metod


Checks whether a password is correct for a presentation protected with open password.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet att kontrollera. |

### Returvärde

True if the presentation is protected with open password and the password is correct and false otherwise.
## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



When the password is null or empty, this method returns false. 
## Se även

* Klass [String](../../../system/string/)
* Klass [IPresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)