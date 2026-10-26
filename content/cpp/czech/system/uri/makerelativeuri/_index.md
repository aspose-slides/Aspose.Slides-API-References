---
title: MakeRelativeUri()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje rozdíl mezi URI reprezentovanými aktuálním a specifikovaným objektem Uri.
type: docs
weight: 352
url: /cs/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metoda

Určuje rozdíl mezi URI reprezentovanými aktuálním a zadaným [Uri](../) objektem.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Porovnávaný |

### Návratová hodnota

Pokud jsou hostitelské jméno a schéma URI reprezentovaných aktuálním objektem a **toUri** stejné, pak tato metoda vrací relativní [Uri](../), který po připojení k aktuální instanci URI vytvoří **toUri**. Pokud se hostitelské jméno nebo schéma liší, pak tato metoda vrací objekt [Uri](../), který představuje parametr **uri**.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Uri](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)