---
title: MakeRelative()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer skillnaden mellan två Uri-instans.
type: docs
weight: 365
url: /sv/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metod

Bestämmer skillnaden mellan två [Uri](../)-instanser.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI:n att jämföra med den aktuella URI:n |

### Returvärde

Om värdnamnet och schemat för de URI:er som representeras av det aktuella objektet och **toUri** är desamma, returnerar denna metod ett [String](../../string/) som representerar en relativ [Uri](../), när den läggs till den aktuella URI-instansen, ger **toUri**. Om värdnamnet eller schemat är olika, returnerar denna metod ett [String](../../string/) som representerar **uri**-parametern.

## Se också

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Uri](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)