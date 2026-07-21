---
title: CreateDecryptor()
second_title: Aspose.Slides для C++ справка по API
description: Создает объект дешифратора с явными параметрами.
type: docs
weight: 14
url: /ru/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод


Создает объект дешифратора с явными параметрами.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ключ шифрования в виде массива байт. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Начальное значение в виде массива байт. |

### Возвращаемое значение

Новосозданный объект дешифратора.

## RijndaelManaged::CreateDecryptor() метод


Создает объект дешифратора с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод


Создает объект дешифратора с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../../icryptotransform/)
* Класс [RijndaelManaged](../)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)