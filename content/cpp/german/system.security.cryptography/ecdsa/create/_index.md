---
title: Create()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt die standardmäßige ECDSA-Algorithmus-Implementierung.
type: docs
weight: 131
url: /de/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() Methode

Erstellt die standardmäßige ECDSA-Algorithmus-Implementierung.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Rückgabewert

ECDSA-Algorithmusobjekt.

## ECDsa::Create(const ECCurve\&) Methode

Erstellt die standardmäßige ECDSA-Algorithmus-Implementierung mit einem neu erstellten Schlüssel über die angegebene Kurve.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Kurve, die für die Schlüsselerstellung verwendet wird. |

### Rückgabewert

ECDSA-Algorithmusobjekt.

## ECDsa::Create(const ECParameters\&) Methode

Erstellt die standardmäßige ECDSA-Algorithmus-Implementierung unter Verwendung der angegebenen Parameter.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parameter, die den Schlüssel darstellen. |

### Rückgabewert

ECDSA-Algorithmusobjekt.

## ECDsa::Create(const String\&) Methode

Erstellt die angegebene ECDSA-Algorithmus-Implementierung.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algorithmusname. |

### Rückgabewert

ECDSA-Algorithmusobjekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ECDsa](../)
* Klasse [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)