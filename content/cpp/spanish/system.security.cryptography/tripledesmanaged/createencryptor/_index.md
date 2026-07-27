---
title: CreateEncryptor()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto cifrador con parámetros explícitos.
type: docs
weight: 1
url: /es/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

Crea un objeto cifrador con parámetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Clave de cifrado en forma de arreglo de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial en forma de arreglo de bytes. |

### Valor devuelto

Objeto cifrador recién creado.

## TripleDESManaged::CreateEncryptor() method

Crea un objeto cifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

Crea un objeto cifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../../icryptotransform/)
* Clase [TripleDESManaged](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)