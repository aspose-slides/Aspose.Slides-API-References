---
title: Create()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр XmlReader с указанным URI.
type: docs
weight: 1015
url: /ru/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) метод

Создает новый [XmlReader](../) экземпляр с указанным URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI для файла, содержащего данные XML. Класс [XmlUrlResolver](../../xmlurlresolver/) используется для преобразования пути в каноническое представление данных. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный URI и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI для файла, содержащего данные XML. Объект [XmlResolver](../../xmlresolver/) на объекте [XmlReaderSettings](../../xmlreadersettings/) используется для преобразования пути в каноническое представление данных. Если значение XmlReaderSettings::get_XmlResolver равно **nullptr**, используется новый объект [XmlUrlResolver](../../xmlurlresolver/). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный URI, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI для файла, содержащего данные XML. Объект [XmlResolver](../../xmlresolver/) на объекте [XmlReaderSettings](../../xmlreadersettings/) используется для преобразования пути в каноническое представление данных. Если значение XmlReaderSettings::get_XmlResolver равно **nullptr**, используется новый объект [XmlUrlResolver](../../xmlurlresolver/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Контекстная информация, необходимая для разбора XML-фрагмента. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область пространства имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный поток с настройками по умолчанию.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные XML. [XmlReader](../) сканирует первые байты потока в поиске маркера порядка байт или другого признака кодировки. После определения кодировки она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) метод

Создает новый [XmlReader](../) экземпляр с указанным потоком и настройками.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные XML. [XmlReader](../) сканирует первые байты потока в поиске маркера порядка байт или другого признака кодировки. После определения кодировки она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный поток, базовый URI и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные XML. [XmlReader](../) сканирует первые байты потока в поиске маркера порядка байт или другого признака кодировки. После определения кодировки она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Базовый URI для сущности или документа, который читается. Это значение может быть **nullptr**. **[Security](../../../system.security/) Примечание** Базовый URI используется для разрешения относительного URI XML-документа. Не используйте базовый URI из недоверенного источника. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный поток, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные XML. [XmlReader](../) сканирует первые байты потока в поиске маркера порядка байт или другого признака кодировки. После определения кодировки она используется для продолжения чтения потока, и обработка продолжается, разбирая ввод как поток (Unicode) символов. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового экземпляра [XmlReader](../). Это значение может быть **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Контекстная информация, необходимая для разбора XML-фрагмента. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область пространства имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный текстовый читатель.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode-символов, поэтому кодировка, указанная в объявлении XML, не используется XML-читателем для декодирования потока данных. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный текстовый читатель и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode-символов, поэтому кодировка, указанная в объявлении XML, не используется XML-читателем для декодирования потока данных. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | Настройки для нового [XmlReader](../). Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный текстовый читатель, настройки и базовый URI.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode-символов, поэтому кодировка, указанная в объявлении XML, не используется [XmlReader](../) для декодирования потока данных. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового [XmlReader](../) экземпляра. Это значение может быть **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | Базовый URI для сущности или документа, который читается. Это значение может быть **nullptr**. **[Security](../../../system.security/) Примечание** Базовый URI используется для разрешения относительного URI XML-документа. Не используйте базовый URI из недоверенного источника. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) метод

Создает новый [XmlReader](../) экземпляр, используя указанный текстовый читатель, настройки и контекстную информацию для разбора.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Текстовый читатель, из которого читаются данные XML. Текстовый читатель возвращает поток Unicode-символов, поэтому кодировка, указанная в объявлении XML, не используется XML-читателем для декодирования потока данных. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового [XmlReader](../) экземпляра. Это значение может быть **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Контекстная информация, необходимая для разбора XML-фрагмента. Контекст может включать [XmlNameTable](../../xmlnametable/) для использования, кодировку, область пространства имён, текущие области **xml:lang** и **xml:space**, базовый URI и определение типа документа. Это значение может быть **nullptr**. |

### Возвращаемое значение

Объект, используемый для чтения данных XML из потока.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) метод

Создает новый [XmlReader](../) экземпляр, используя указанный XML-читатель и настройки.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | Объект, который вы хотите использовать в качестве базового XML-читателя. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | Настройки для нового [XmlReader](../) экземпляра. Уровень соответствия объекта [XmlReaderSettings](../../xmlreadersettings/) должен либо совпадать с уровнем соответствия базового читателя, либо быть установлен в [ConformanceLevel::Auto](../../conformancelevel/). |

### Возвращаемое значение

Объект, обёрнутый вокруг указанного [XmlReader](../) объекта.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Class [XmlReaderSettings](../../xmlreadersettings/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)