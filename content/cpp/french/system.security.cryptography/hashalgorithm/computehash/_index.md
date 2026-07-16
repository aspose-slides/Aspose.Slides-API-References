---
title: ComputeHash()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule le hachage du tampon.
type: docs
weight: 14
url: /fr/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) méthode

Calcule le hachage du tampon.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tampon source. |

### Valeur de retour

Valeur de hachage calculée.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) méthode

Calcule le hachage d’une tranche du tampon.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tampon source. |
| offset | int | Décalage dans le tampon source. |
| count | int | Nombre d’octets à utiliser du tampon source. |

### Valeur de retour

Valeur de hachage calculée.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) méthode

Lit le flux jusqu’à la fin et calcule le hachage des données lues.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Flux à partir duquel lire les données. |

### Valeur de retour

Valeur de hachage calculée pour l’ensemble des données du flux.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [HashAlgorithm](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)