---
title: CreateEncryptor()
second_title: Aspose.Slides для C++ справочник API
description: Создает шифратор с параметрами, связанными с объектом алгоритма.
type: docs
weight: 183
url: /ru/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() метод

Создаёт шифратор с параметрами, связанными с объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### Возвращаемое значение

Новосозданный объект шифратора.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создаёт шифратор с явными параметрами.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ключ для использования. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Начальное значение для использования. |

### Возвращаемое значение

Новосозданный объект шифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../../icryptotransform/)
* Класс [SymmetricAlgorithm](../)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)