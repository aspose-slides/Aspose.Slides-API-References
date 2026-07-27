---
title: CreateDecryptor()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto descifrador con parámetros explícitos.
type: docs
weight: 14
url: /es/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con parámetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Clave de cifrado en forma de matriz de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial en forma de matriz de bytes. |

### Return Value

Valor devuelto

Objeto descifrador recién creado.

## TripleDESManaged::CreateDecryptor() método

Crea un objeto descifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../../icryptotransform/)
* Clase [TripleDESManaged](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)