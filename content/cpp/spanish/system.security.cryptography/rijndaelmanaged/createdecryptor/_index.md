---
title: CreateDecryptor()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un objeto descifrador con parámetros explícitos.
type: docs
weight: 14
url: /es/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con parámetros explícitos.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Clave de cifrado en forma de arreglo de bytes. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Valor inicial en forma de arreglo de bytes. |

### Valor de retorno

Objeto descifrador recién creado.

## RijndaelManaged::CreateDecryptor() método

Crea un objeto descifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) método

Crea un objeto descifrador con los parámetros definidos por el objeto algoritmo.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [ICryptoTransform](../../icryptotransform/)
* Clase [RijndaelManaged](../)
* Espacio de nombres [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)