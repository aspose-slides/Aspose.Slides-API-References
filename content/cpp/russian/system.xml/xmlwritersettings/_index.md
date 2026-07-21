---
title: XmlWriterSettings
second_title: Справочник API Aspose.Slides для C++
description: "Указывает набор возможностей, поддерживаемых объектом XmlWriter, созданным методом XmlWriter::Create."
type: docs
weight: 586
url: /ru/system.xml/xmlwritersettings/
---
## XmlWriterSettings класс

Указывает набор возможностей, поддерживаемых объектом [XmlWriter](../xmlwriter/), созданным методом [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Создает копию экземпляра [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Возвращает значение, указывающее, должен ли XML-писатель проверять, чтобы все символы в документе соответствовали разделу "2.2 Characters" спецификации W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Возвращает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) также закрывать базовый поток или TextWriter при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Возвращает уровень соответствия, который XML-писатель проверяет в выводе XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Возвращает значение, указывающее, не экранирует ли [XmlWriter](../xmlwriter/) URI-атрибуты. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Возвращает тип кодировки текста, который следует использовать. |
| **bool** [get_Indent](./get_indent/)() | Возвращает значение, указывающее, следует ли делать отступы у элементов. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Возвращает строку символов, используемую для отступов. Эта настройка применяется, когда значение [XmlWriterSettings::set_Indent](./set_indent/) установлено в **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Возвращает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) удалять дублирующие объявления пространств имён при записи XML-содержимого. Поведение по умолчанию — писатель выводит все объявления пространств имён, присутствующие в разрешателе пространств имён писателя. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Возвращает строку символов, используемую для разрывов строк. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Возвращает значение, указывающее, следует ли нормализовать разрывы строк в выводе. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Возвращает значение, указывающее, следует ли записывать атрибуты на новой строке. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Возвращает значение, указывающее, следует ли опустить объявление XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Возвращает метод, используемый для сериализации вывода [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Возвращает значение, указывающее, будет ли [XmlWriter](../xmlwriter/) добавлять закрывающие теги ко всем незакрытым элементам при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [Reset](./reset/)() | Сбрасывает члены класса настроек к их значениям по умолчанию. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Устанавливает значение, указывающее, должен ли XML-писатель проверять, чтобы все символы в документе соответствовали разделу "2.2 Characters" спецификации W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets). |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Устанавливает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) также закрывать базовый поток или TextWriter при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Устанавливает уровень соответствия, который XML-писатель проверяет в выводе XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Устанавливает значение, указывающее, не экранирует ли [XmlWriter](../xmlwriter/) URI-атрибуты. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Устанавливает тип кодировки текста, который следует использовать. |
| void [set_Indent](./set_indent/)(**bool**) | Устанавливает значение, указывающее, следует ли делать отступы у элементов. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Устанавливает строку символов, используемую для отступов. Эта настройка применяется, когда значение [XmlWriterSettings::set_Indent](./set_indent/) установлено в **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Устанавливает значение, указывающее, должен ли [XmlWriter](../xmlwriter/) удалять дублирующие объявления пространств имён при записи XML-содержимого. Поведение по умолчанию — писатель выводит все объявления пространств имён, присутствующие в разрешателе пространств имён писателя. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Устанавливает строку символов, используемую для разрывов строк. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Устанавливает значение, указывающее, следует ли нормализовать разрывы строк в выводе. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Устанавливает значение, указывающее, следует ли записывать атрибуты на новой строке. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Устанавливает значение, указывающее, следует ли опустить объявление XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Устанавливает значение, указывающее, будет ли [XmlWriter](../xmlwriter/) добавлять закрывающие теги ко всем незакрытым элементам при вызове метода [XmlWriter::Close](../xmlwriter/close/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Инициализирует новый экземпляр класса [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типedefs

| Типedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для умного указателя на экземпляр этого класса. |

## Примечания

Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам во время выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. 

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)