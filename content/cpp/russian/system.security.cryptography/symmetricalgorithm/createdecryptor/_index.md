---
title: CreateDecryptor()
second_title: Aspose.Slides для C++ справочник API
description: Создает дешифратор с параметрами, связанными с объектом алгоритма.
type: docs
weight: 196
url: /ru/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() метод

Создает дешифратор с параметрами, связанными с объектом алгоритма.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Возвращаемое значение

Новосозданный объект дешифратора.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) метод

Создает дешифратор с явными параметрами.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Key to use. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initial value to use. |

### Возвращаемое значение

Новосозданный объект дешифратора.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICryptoTransform](../../icryptotransform/)
* Класс [SymmetricAlgorithm](../)
* Пространство имён [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)