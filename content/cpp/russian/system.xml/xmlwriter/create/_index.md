---
title: Create()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый экземпляр XmlWriter, используя указанный файл.
type: docs
weight: 469
url: /ru/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанного имени файла.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Файл, в который вы хотите записать. [XmlWriter](../) создает файл по указанному пути и записывает в него в текстовом синтаксисе XML 1.0. **outputFileName** должен быть путем к файловой системе. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) метод

Создает новый экземпляр [XmlWriter](../) с использованием имени файла и объекта [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Файл, в который вы хотите записать. [XmlWriter](../) создает файл по указанному пути и записывает в него в текстовом синтаксисе XML 1.0. **outputFileName** должен быть путем к файловой системе. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) объект, используемый для настройки нового экземпляра [XmlWriter](../). Если он **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) вы должны использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с правильными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанного потока.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите записать. [XmlWriter](../) записывает в поток текстовый синтаксис XML 1.0. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) метод

Создает новый экземпляр [XmlWriter](../) с использованием потока и объекта [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите записать. [XmlWriter](../) записывает в поток текстовый синтаксис XML 1.0. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) объект, используемый для настройки нового экземпляра [XmlWriter](../). Если он **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) вы должны использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с правильными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанного TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, в который вы хотите записать. [XmlWriter](../) записывает в TextWriter текстовый синтаксис XML 1.0. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) метод

Создает новый экземпляр [XmlWriter](../) с использованием TextWriter и объектов [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, в который вы хотите записать. [XmlWriter](../) записывает в TextWriter текстовый синтаксис XML 1.0. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) объект, используемый для настройки нового экземпляра [XmlWriter](../). Если он **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) вы должны использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с правильными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанного [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) для записи. Содержимое, записанное [XmlWriter](../), добавляется к [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) метод

Создает новый экземпляр [XmlWriter](../) с использованием объектов [Text::StringBuilder](../../../system.text/stringbuilder/) и [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | [Text::StringBuilder](../../../system.text/stringbuilder/) для записи. Содержимое, записанное [XmlWriter](../), добавляется к [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) объект, используемый для настройки нового экземпляра [XmlWriter](../). Если он **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) вы должны использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с правильными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### Return Value

An [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанного объекта [XmlWriter](../).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Объект [XmlWriter](../), который вы хотите использовать в качестве базового записывателя. |

### Return Value

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) метод

Создает новый экземпляр [XmlWriter](../) с использованием указанных объектов [XmlWriter](../) и [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Объект [XmlWriter](../), который вы хотите использовать в качестве базового записывателя. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | [XmlWriterSettings](../../xmlwritersettings/) объект, используемый для настройки нового экземпляра [XmlWriter](../). Если он **nullptr**, используется [XmlWriterSettings](../../xmlwritersettings/) с настройками по умолчанию. Если [XmlWriter](../) используется с методом XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) вы должны использовать значение XslCompiledTransform::get_OutputSettings для получения объекта [XmlWriterSettings](../../xmlwritersettings/) с правильными настройками. Это гарантирует, что созданный объект [XmlWriter](../) имеет правильные параметры вывода. |

### Return Value

An [XmlWriter](../) object that is wrapped around the specified [XmlWriter](../) object.

## See Also

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlWriter](../)
* Класс [String](../../../system/string/)
* Класс [XmlWriterSettings](../../xmlwritersettings/)
* Класс [Stream](../../../system.io/stream/)
* Класс [TextWriter](../../../system.io/textwriter/)
* Класс [StringBuilder](../../../system.text/stringbuilder/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)