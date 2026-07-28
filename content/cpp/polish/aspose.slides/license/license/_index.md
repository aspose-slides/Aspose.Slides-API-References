---
title: License()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Inicjalizuje nową instancję tej klasy.
type: docs
weight: 1
url: /pl/aspose.slides/license/license/
---
## License::License() konstruktor

Inicjalizuje nową instancję tej klasy.

```cpp
Aspose::Slides::License::License()
```

## Uwagi

W tym przykładzie podejmowana jest próba znalezienia pliku licencji o nazwie MyLicense.lic w folderze zawierającym komponent, w folderze zawierającym wywołującą assembly, w folderze entry assembly i następnie w osadzonych zasobach wywołującej assembly.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Zobacz także

* Klasa [License](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)