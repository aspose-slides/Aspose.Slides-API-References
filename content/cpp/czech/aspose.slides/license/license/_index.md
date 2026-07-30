---
title: License()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializuje novou instanci této třídy.
type: docs
weight: 1
url: /cs/aspose.slides/license/license/
---
## License::License() konstruktor

Inicializuje novou instanci této třídy.

```cpp
Aspose::Slides::License::License()
```

## Poznámky

V tomto příkladu bude provedeno pokus najít licenční soubor pojmenovaný MyLicense.lic ve složce, která obsahuje komponentu, ve složce, která obsahuje volající sestavení, ve složce vstupního sestavení a poté v vložených zdrojích volajícího sestavení. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Viz také

* Třída [License](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)