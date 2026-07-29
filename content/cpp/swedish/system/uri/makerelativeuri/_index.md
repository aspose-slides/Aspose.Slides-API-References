---
title: MakeRelativeUri()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer skillnaden mellan URI:er som representeras av det aktuella och de angivna Uri-objekten.
type: docs
weight: 352
url: /sv/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) metod

Bestämmer skillnaden mellan URI:er som representeras av det aktuella och det angivna [Uri](../)-objektet.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Jämförelseobjektet |

### Return Value

Om värdnamnet och schemat för de URI:er som representeras av det aktuella objektet och **toUri** är desamma, returnerar den här metoden ett relativt [Uri](../) som, när det läggs till den aktuella URI-instansen, ger **toUri**. Om värdnamnet eller schemat är olika, returnerar den här metoden ett [Uri](../)-objekt som representerar **uri**-parametern.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)