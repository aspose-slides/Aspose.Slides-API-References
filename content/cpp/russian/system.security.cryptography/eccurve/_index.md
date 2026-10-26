---
title: ECCurve
second_title: Aspose.Slides для C++ справочник API
description: Эллиптическая кривая.
type: docs
weight: 716
url: /ru/system.security.cryptography/eccurve/
---
## ECCurve struct

Эллиптическая кривая.

```cpp
class ECCurve
```

## Методы

| Метод | Описание |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Создать кривую из указанного дружелюбного имени OID. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Создать кривую из указанного oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Создать кривую из указанного значения OID. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Получает [Oid](../oid/), представляющий именованную кривую. |
| void [Validate](./validate/)() const | Проверить текущую кривую. |
## Перечисления

| Перечисление | Описание |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Тип эллиптической кривой. |
## См. также

* Пространство имён [System::Security::Cryptography](../)
* Библиотека [Aspose.Slides](../../)