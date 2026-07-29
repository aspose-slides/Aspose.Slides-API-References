---
title: License()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av den här klassen.
type: docs
weight: 1
url: /sv/aspose.slides/license/license/
---
## License::License() konstruktor

Initierar en ny instans av den här klassen.

```cpp
Aspose::Slides::License::License()
```

## Anmärkningar

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna i den anropande samlingen.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Se även

* Klass [License](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)