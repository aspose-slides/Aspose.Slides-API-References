---
title: CreateDecryptor()
second_title: Справочник API Aspose.Slides для C++
description: Создает объект дешифратора с явными параметрами.
type: docs
weight: 14
url: /ru/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создает объект дешифратора с явными параметрами.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ключ шифрования в виде массива байтов. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Начальное значение в виде массива байтов. |

### Возвращаемое значение

Новосозданный объект дешифратора.

## RC2Managed::CreateDecryptor() метод

Создает объект дешифратора с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создает объект дешифратора с параметрами, определенными объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../../icryptotransform/)
* Класс [RC2Managed](../)
* Пространство имен [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)