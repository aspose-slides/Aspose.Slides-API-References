---
title: WriteRaw()
second_title: Справочник API Aspose.Slides for C++
description: Записывает необработанную разметку вручную из буфера символов.
type: docs
weight: 417
url: /ru/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) метод

Записывает необработанную разметку вручную из буфера символов.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Массив символов, содержащий текст для записи. |
| index | **int32_t** | Позиция в буфере, указывающая начало текста для записи. |
| count | **int32_t** | Количество символов для записи. |

## XmlTextWriter::WriteRaw(const String\&) метод

Записывает необработанную разметку вручную из строки.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) содержащий текст для записи. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlTextWriter](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)