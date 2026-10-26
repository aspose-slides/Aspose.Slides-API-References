---
title: Create()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea l'implementazione predefinita dell'algoritmo ECDSA.
type: docs
weight: 131
url: /it/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() method

Crea l'implementazione predefinita dell'algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Valore di ritorno

ECDSA algorithm object.

## ECDsa::Create(const ECCurve\&) method

Crea l'implementazione predefinita dell'algoritmo ECDSA con una chiave appena creata sulla curva specificata.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curva da usare per la creazione della chiave. |

### Valore di ritorno

ECDSA algorithm object.

## ECDsa::Create(const ECParameters\&) method

Crea l'implementazione predefinita dell'algoritmo ECDSA utilizzando i parametri specificati.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametri che rappresentano la chiave. |

### Valore di ritorno

ECDSA algorithm object.

## ECDsa::Create(const String\&) method

Crea l'implementazione specificata dell'algoritmo ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nome dell'algoritmo. |

### Valore di ritorno

ECDSA algorithm object.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ECDsa](../)
* Classe [String](../../../system/string/)
* Struttura [ECCurve](../../eccurve/)
* Struttura [ECParameters](../../ecparameters/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)