---
title: CreateEncryptor()
second_title: Справочник API Aspose.Slides для C++
description: Создает объект шифрования с явными параметрами.
type: docs
weight: 1
url: /ru/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создает объект шифрования с явными параметрами.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ключ шифрования в виде массива байтов. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Начальное значение в виде массива байтов. |

### Возвращаемое значение

Новосозданный объект шифрования.

## RC2Managed::CreateEncryptor() метод

Создает объект шифрования с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создает объект шифрования с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../../icryptotransform/)
* Класс [RC2Managed](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)