---
title: Create()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy domyślną implementację algorytmu ECDSA.
type: docs
weight: 131
url: /pl/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() metoda

Tworzy domyślną implementację algorytmu ECDSA aglorithm.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Wartość zwracana

Obiekt algorytmu ECDSA.

## ECDsa::Create(const ECCurve\&) metoda

Tworzy domyślną implementację algorytmu ECDSA aglorithm z nowo utworzonym kluczem na określonej krzywej.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Krzywa używana do tworzenia klucza. |

### Wartość zwracana

Obiekt algorytmu ECDSA.

## ECDsa::Create(const ECParameters\&) metoda

Tworzy domyślną implementację algorytmu ECDSA aglorithm przy użyciu określonych parametrów.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametry reprezentujące klucz. |

### Wartość zwracana

Obiekt algorytmu ECDSA.

## ECDsa::Create(const String\&) metoda

Tworzy określoną implementację algorytmu ECDSA aglorithm.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nazwa algorytmu. |

### Wartość zwracana

Obiekt algorytmu ECDSA.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ECDsa](../)
* Klasa [String](../../../system/string/)
* Struktura [ECCurve](../../eccurve/)
* Struktura [ECParameters](../../ecparameters/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)