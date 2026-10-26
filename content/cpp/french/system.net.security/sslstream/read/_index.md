---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit le nombre spécifié d'octets depuis le flux et les écrit dans le tableau d'octets spécifié.
type: docs
weight: 391
url: /fr/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d’octets depuis le flux et les écrit dans le tableau d’octets spécifié.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d’octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position indexée à 0 dans **buffer** où commencer l’écriture |
| count | **int32_t** | Le nombre d’octets à lire |

### Valeur de retour

Le nombre d’octets lus

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit le nombre spécifié d’octets depuis le flux et les écrit dans le tableau d’octets spécifié.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Le tableau d’octets dans lequel écrire les octets lus |
| offset | **int32_t** | Une position indexée à 0 dans **buffer** où commencer l’écriture |
| count | **int32_t** | Le nombre d’octets à lire |

### Valeur de retour

Le nombre d’octets lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [SslStream](../)
* Espace de noms [System::Net::Security](../../)
* Bibliothèque [Aspose.Slides](../../../)