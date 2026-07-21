---
title: Create()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт реализацию алгоритма ECDSA по умолчанию.
type: docs
weight: 131
url: /ru/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() метод

Создаёт реализацию алгоритма ECDSA по умолчанию.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Возвращаемое значение

Объект алгоритма ECDSA.

## ECDsa::Create(const ECCurve\&) метод

Создаёт реализацию алгоритма ECDSA по умолчанию с новым ключом, созданным над указанной кривой.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Кривая, используемая для создания ключа. |

### Возвращаемое значение

Объект алгоритма ECDSA.

## ECDsa::Create(const ECParameters\&) метод

Создаёт реализацию алгоритма ECDSA по умолчанию, используя указанные параметры.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Параметры, представляющие ключ. |

### Возвращаемое значение

Объект алгоритма ECDSA.

## ECDsa::Create(const String\&) метод

Создаёт указанную реализацию алгоритма ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Имя алгоритма. |

### Возвращаемое значение

Объект алгоритма ECDSA.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ECDsa](../)
* Класс [String](../../../system/string/)
* Структура [ECCurve](../../eccurve/)
* Структура [ECParameters](../../ecparameters/)
* Пространство имён [System::Security::Cryptography](../../)
* Библиотека [Aspose.Slides](../../../)