---
title: MakeRelative()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a két Uri példány közötti különbséget.
type: docs
weight: 365
url: /hu/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metódus

Meghatározza a különbséget két [Uri](../) példány között.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az URI, amelyhez az aktuális URI-t összehasonlítjuk |

### Visszatérési érték

Ha az aktuális objektum és a **toUri** által képviselt URI-k hostneve és sémája megegyezik, akkor ez a metódus egy [String](../../string/)-t ad vissza, amely egy relatív [Uri](../)-t képvisel, és ha az aktuális URI példányhoz hozzáfűzöd, az **toUri**-t eredményezi. Ha a hostnév vagy a séma eltér, akkor ez a metódus egy [String](../../string/)-t ad vissza, amely a **uri** paramétert képviseli.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Uri](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)