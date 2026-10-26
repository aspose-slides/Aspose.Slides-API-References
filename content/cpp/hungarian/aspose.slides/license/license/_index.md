---
title: License()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új példányt ebből az osztályból.
type: docs
weight: 1
url: /hu/aspose.slides/license/license/
---
## License::License() konstruktor


Létrehoz egy új példányt ebből az osztályból.

```cpp
Aspose::Slides::License::License()
```

## Megjegyzések


Ebben a példában megpróbálja megtalálni a MyLicense.lic nevű licenszfájlt a komponenst tartalmazó mappában, a hívó assemblyt tartalmazó mappában, a belépési assembly mappájában, majd a hívó assembly beágyazott erőforrásaiban.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## Lásd még

* Osztály [License](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)