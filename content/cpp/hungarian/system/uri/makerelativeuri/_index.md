---
title: MakeRelativeUri()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a jelenlegi és a megadott Uri objektumok által képviselt URI-k közötti különbséget.
type: docs
weight: 352
url: /hu/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metódus


Meghatározza a jelenlegi és a megadott [Uri](../) objektumok által képviselt URI-k közötti különbséget.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Az összehasonlítandó |

### Visszatérési érték

Ha a jelenlegi objektum által képviselt URI-k és a **toUri** hostneve és sémája megegyezik, akkor ez a metódus egy relatív [Uri](../)-t ad vissza, amely a jelenlegi URI példányhoz hozzáadva **toUri**-t eredményez. Ha a hostnév vagy a séma eltér, akkor ez a metódus egy [Uri](../) objektumot ad vissza, amely a **uri** paramétert reprezentálja.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Uri](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)