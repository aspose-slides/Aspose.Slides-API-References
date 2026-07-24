---
title: MakeRelative()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt die Differenz zwischen zwei Uri-Instanzen.
type: docs
weight: 365
url: /de/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) Methode


Bestimmt die Differenz zwischen zwei [Uri](../) Instanzen.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Die URI, die mit der aktuellen URI verglichen wird. |

### Rückgabewert

Wenn der Hostname und das Schema der URIs, die durch das aktuelle Objekt und **toUri** repräsentiert werden, gleich sind, gibt diese Methode ein [String](../../string/) zurück, das einen relativen [Uri](../) darstellt, der, wenn er an die aktuelle URI-Instanz angehängt wird, **toUri** ergibt. Wenn der Hostname oder das Schema unterschiedlich ist, gibt diese Methode ein [String](../../string/) zurück, das den **uri**-Parameter darstellt.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Uri](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)