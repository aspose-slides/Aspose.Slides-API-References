---
title: MakeRelative()
second_title: Aspose.Slides pro C++ – reference API
description: Určuje rozdíl mezi dvěma instancemi Uri.
type: docs
weight: 365
url: /cs/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) method

Určuje rozdíl mezi dvěma [Uri](../) instancemi.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI, která se porovnává s aktuálním URI |

### Návratová hodnota

Pokud jsou název hostitele a schéma URI reprezentovaných aktuálním objektem a **toUri** stejné, metoda vrátí [String](../../string/), který představuje relativní [Uri](../), jenž po připojení k aktuální instanci URI dává **toUri**. Pokud se název hostitele nebo schéma liší, metoda vrátí [String](../../string/), který představuje parametr **uri**.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)