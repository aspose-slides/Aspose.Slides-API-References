---
title: CheckPassword()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy egy jelszó helyes-e egy nyílt jelszóval védett bemutató esetén.
type: docs
weight: 53
url: /hu/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) metódus


Ellenőrzi, hogy egy jelszó helyes-e egy nyílt jelszóval védett bemutató esetén.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Az ellenőrzendő jelszó. |

### Visszatérési érték

True, ha a bemutató nyílt jelszóval van védve és a jelszó helyes, egyébként false.

## Megjegyzések



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza. 

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [PresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)