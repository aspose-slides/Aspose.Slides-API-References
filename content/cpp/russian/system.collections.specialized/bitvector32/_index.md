---
title: BitVector32
second_title: Aspose.Slides для C++ Справочник API
description: Предоставляет простой лёгкий битовый вектор с лёгким целочисленным или логическим доступом к 32-битному хранилищу.
type: docs
weight: 1
url: /ru/system.collections.specialized/bitvector32/
---
## BitVector32 класс

Provides a simple light bit vector with easy integer or [Boolean](../../system/boolean/) access to a 32 bit storage.

```cpp
class BitVector32
```

## Методы

| Метод | Описание |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Инициализирует новый пустой экземпляр [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Инициализирует новый экземпляр структуры [BitVector32](./) с указанными внутренними данными. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Инициализирует новый экземпляр структуры [BitVector32](./) с информацией из указанного значения. |
| static **int32_t** [CreateMask](./createmask/)() | Создаёт первую маску в серии. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Создаёт следующую маску в серии. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Создаёт первую секцию в серии с указанным максимальным значением. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Создаёт следующую секцию в серии с указанным максимальным значением. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Определяет, является ли указанный объект тем же, что и текущий. |
| **int32_t** [get_Data](./get_data/)() | возвращает необработанные данные, хранящиеся в этом битовом векторе... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Возвращает хеш-код текущего объекта. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Получает значение, указывающее, установлены ли все указанные биты. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Получает значение для указанной секции. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Устанавливает значение, указывающее, установлены ли все указанные биты. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Устанавливает значение для указанной секции. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Преобразует значение, представленное параметром value, в строку. |
| [String](../../system/string/) [ToString](./tostring/)() const | Преобразует значение, представленное текущим объектом, в строку. |
## См. также

* Пространство имён [System::Collections::Specialized](../)
* Библиотека [Aspose.Slides](../../)