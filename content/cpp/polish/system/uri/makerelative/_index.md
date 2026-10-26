---
title: MakeRelative()
second_title: Aspose.Slides dla C++ – Referencja API
description: Określa różnicę między dwoma instancjami Uri.
type: docs
weight: 365
url: /pl/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) metoda

Określa różnicę między dwoma [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI, które ma być porównane z bieżącym URI |

### Wartość zwracana

Jeśli nazwa hosta i schemat URI reprezentowanych przez bieżący obiekt oraz **toUri** są takie same, ta metoda zwraca [String](../../string/) reprezentujący względny [Uri](../), który po dołączeniu do bieżącej instancji URI daje **toUri**. Jeśli nazwa hosta lub schemat jest inny, ta metoda zwraca [String](../../string/) reprezentujący parametr **uri**.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)