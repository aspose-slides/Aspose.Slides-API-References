---
title: DocumentProperties
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства презентации.
type: docs
weight: 794
url: /ru/aspose.slides/documentproperties/
---
## DocumentProperties класс

Представляет свойства презентации.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Очищает и задаёт значения по умолчанию для всех встроенных свойств. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Удаляет все пользовательские свойства. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Клонирует текущий объект |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Клонирует текущий объект |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Проверяет наличие пользовательского свойства с указанным именем. |
| [DocumentProperties](./documentproperties/)() | Инициализирует новый экземпляр класса [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает ссылки на объекты в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты-значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Возвращает шаблон приложения. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Возвращает версию приложения. Только для чтения [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Возвращает автора презентации. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Возвращает категорию презентации. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Возвращает комментарии к презентации. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Возвращает свойство компании. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Возвращает статус содержимого презентации. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Возвращает тип содержимого презентации. Читать [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Возвращает количество пользовательских свойств, действительно содержащихся в коллекции. Только для чтения **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Возвращает дату создания презентации. Значения в UTC. Читать [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Указывает группировку частей документа и количество частей в каждой группе. Только для чтения [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Возвращает количество скрытых слайдов в документе презентации. Только для чтения **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Возвращает свойство HyperlinkBase документа. Читать [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, обновит отношения гиперссылок новыми гиперссылками, указанными в этой части. Читать **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Возвращает ключевые слова презентации. Читать [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Возвращает дату последней печати презентации. Читать [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Возвращает имя последнего лица, изменившего презентацию. Читать [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (поскольку будет обновлено внутренне во время процесса сохранения объекта [IPresentation](../ipresentation/)). Может быть изменено через экземпляр [DocumentProperties](./), возвращаемый методом [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). См. пример в сводке метода [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Указывает, актуальны ли гиперссылки в документе. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите в **false**, чтобы указать, что гиперссылки устарели. Читать **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Возвращает свойство менеджера. Читать [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Возвращает общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Возвращает имя приложения. Читать [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Возвращает количество слайдов в презентации, содержащих заметки. Только для чтения **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Возвращает общее количество абзацев в документе, если применимо. Только для чтения **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Возвращает предполагаемый формат презентации. Читать [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Возвращает номер ревизии презентации. Читать **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Указывает режим отображения миниатюры документа. Установите элемент в **true**, чтобы включить масштабирование миниатюры к дисплею. Установите в **false**, чтобы включить обрезку миниатюры, показывая только те части, которые помещаются в дисплей. Читать **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Определяет, общая ли презентация между несколькими пользователями. Читать **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Возвращает общее количество слайдов в документе презентации. Только для чтения **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Возвращает тему презентации. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Возвращает название презентации. Читать [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Указывает название каждой части документа. Эти части не являются реальными частями документа, а концептуальными представлениями разделов документа. Только для чтения [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Общее время редактирования презентации. Читать [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Возвращает общее количество слов в документе. Только для чтения **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Возвращает имя пользовательского свойства по указанному индексу. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Получает именованное булево значение из пользовательских свойств. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Получает именованное целочисленное значение из пользовательских свойств. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Получает именованное значение DateTime из пользовательских свойств. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Получает именованное строковое значение из пользовательских свойств. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Получает именованное значение float из пользовательских свойств. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Получает именованное значение double из пользовательских свойств. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Получает массив меток чувствительности из пользовательских свойств документа (Metadata SDK Microsoft Information Protection). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Возвращает пользовательское свойство, связанное с указанным именем. Читать [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Устанавливает пользовательское свойство, связанное с указанным именем. Запись [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует оператор C# lock() для блокировки. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект-значение с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строка и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Удаляет пользовательское свойство, связанное с указанным именем. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Устанавливает шаблон приложения. Запись [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Устанавливает автора презентации. Запись [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Устанавливает категорию презентации. Запись [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Устанавливает комментарии к презентации. Запись [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Устанавливает свойство компании. Запись [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Устанавливает статус содержимого презентации. Запись [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Устанавливает тип содержимого презентации. Запись [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Устанавливает дату создания презентации. Значения в UTC. Запись [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Устанавливает свойство HyperlinkBase документа. Запись [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, обновит отношения гиперссылок новыми гиперссылками, указанными в этой части. Запись **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Устанавливает ключевые слова презентации. Запись [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Устанавливает дату последней печати презентации. Запись [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Устанавливает имя последнего лица, изменившего презентацию. Запись [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Устанавливает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (поскольку будет обновлено внутренне во время процесса сохранения объекта [IPresentation](../ipresentation/)). Может быть изменено через экземпляр [DocumentProperties](./), возвращаемый методом [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). См. пример в сводке метода [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Указывает, актуальны ли гиперссылки в документе. Установите этот элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите в **false**, чтобы указать, что гиперссылки устарели. Запись **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Устанавливает свойство менеджера. Запись [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Устанавливает имя приложения. Запись [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Устанавливает предполагаемый формат презентации. Запись [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Устанавливает номер ревизии презентации. Запись **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Указывает режим отображения миниатюры документа. Установите элемент в **true**, чтобы включить масштабирование миниатюры к дисплею. Установите в **false**, чтобы включить обрезку миниатюры, показывая только те части, которые помещаются в дисплей. Запись **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Определяет, общая ли презентация между несколькими пользователями. Запись **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Устанавливает тему презентации. Запись [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Устанавливает название презентации. Запись [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Общее время редактирования презентации. Запись [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Устанавливает именованное булево пользовательское свойство. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Устанавливает именованное целочисленное пользовательское свойство. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Устанавливает именованное пользовательское свойство DateTime. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Устанавливает именованное пользовательское свойство строки. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Устанавливает именованное пользовательское свойство float. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Устанавливает именованное пользовательское свойство double. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует оператор C# lock() для разблокировки. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Следующий пример показывает, как получить доступ к встроенным свойствам PowerPoint [Presentation](../presentation/). 
```cpp
// Создайте объект класса Presentation, представляющий презентацию
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Следующий пример показывает, как изменить встроенные свойства PowerPoint [Presentation](../presentation/). 
```cpp
// Создайте объект класса Presentation, представляющий презентацию
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Создайте ссылку на объект IDocumentProperties, связанный с презентацией
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Установите встроенные свойства
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Сохраните вашу презентацию в файл
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IDocumentProperties](../idocumentproperties/)
* Класс [IGenericCloneable](../igenericcloneable/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)