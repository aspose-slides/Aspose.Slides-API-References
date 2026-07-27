---
title: CreateDecryptor()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un objeto descifrador con parámetros explícitos.
type: docs
weight: 14
url: /es/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con parámetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Clave de cifrado en forma de matriz de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial en forma de matriz de bytes. |

### Valor devuelto

Objeto descifrador recién creado.

## RC2Managed::CreateDecryptor() método

Crea un objeto descifrador con parámetros definidos por el objeto de algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con parámetros definidos por el objeto de algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../../icryptotransform/)
* Clase [RC2Managed](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)