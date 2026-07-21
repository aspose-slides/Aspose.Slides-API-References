---
title: WriteRaw()
second_title: Справочник API Aspose.Slides для C++
description: Когда переопределяется в производном классе, записывает необработанную разметку вручную из буфера символов.
type: docs
weight: 287
url: /ru/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) метод

Когда переопределяется в производном классе, записывает необработанную разметку вручную из буфера символов.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Массив символов, содержащий текст для записи. |
| index | **int32_t** | Позиция в буфере, указывающая начало текста для записи. |
| count | **int32_t** | Количество символов для записи. |

## XmlWriter::WriteRaw(const String\&) метод

Когда переопределяется в производном классе, записывает необработанную разметку вручную из строки.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) содержащая текст для записи. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [XmlWriter](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)