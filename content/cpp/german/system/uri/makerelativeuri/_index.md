---
title: MakeRelativeUri()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt die Differenz zwischen den vom aktuellen und den angegebenen Uri-Objekten dargestellten URIs.
type: docs
weight: 352
url: /de/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) Methode

Bestimmt die Differenz zwischen den vom aktuellen und dem angegebenen [Uri](../)-Objekt dargestellten URIs.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Der Vergleichswert |

### Rückgabewert

Wenn der Hostname und das Schema der von dem aktuellen Objekt und **toUri** dargestellten URIs identisch sind, gibt diese Methode ein relatives [Uri](../) zurück, das, wenn es an die aktuelle URI-Instanz angehängt wird, **toUri** ergibt. Ist der Hostname oder das Schema unterschiedlich, gibt diese Methode ein [Uri](../)-Objekt zurück, das den **uri**-Parameter darstellt.

## Siehe Auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Uri](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)