---
title: CheckPassword()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy egy nyílt jelszóval védett bemutatóhoz a jelszó helyes-e.
type: docs
weight: 53
url: /hu/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) metódus

Ellenőrzi, hogy a jelszó helyes-e egy nyílt jelszóval védett bemutatóhoz.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | A ellenőrzendő jelszó. |

### Visszatérési érték

Igaz, ha a bemutató nyílt jelszóval védett, a jelszó helyes, egyébként hamis.

## Megjegyzések

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Ha a jelszó null vagy üres, ez a metódus hamis értéket ad vissza.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IPresentationInfo](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)