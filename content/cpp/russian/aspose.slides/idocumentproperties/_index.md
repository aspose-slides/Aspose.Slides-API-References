---
title: IDocumentProperties
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства презентации.
type: docs
weight: 1977
url: /ru/aspose.slides/idocumentproperties/
---
## IDocumentProperties класс

Представляет свойства презентации.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Очищает и задает значения по умолчанию для всех встроенных свойств. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Удаляет все пользовательские свойства. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Проверяет наличие пользовательского свойства с указанным именем. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Возвращает шаблон приложения. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Возвращает версию приложения. Только для чтения [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Возвращает автора презентации. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Возвращает категорию презентации. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Возвращает комментарии презентации. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Возвращает свойство компании. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Возвращает статус содержимого презентации. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Возвращает тип содержимого презентации. Читать [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Возвращает количество пользовательских свойств, фактически содержащихся в коллекции. Только для чтения **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Возвращает дату создания презентации. Значения в UTC. Читать [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Указывает группировку частей документа и количество частей в каждой группе. Только для чтения [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Определяет количество скрытых слайдов в документе презентации. Только для чтения **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Возвращает свойство документа HyperlinkBase. Читать [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Читать **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Возвращает ключевые слова презентации. Читать [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Возвращает дату последней печати презентации. Читать [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Возвращает имя последнего человека, изменившего презентацию. Читать [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку будет обновляться внутренне во время процесса сохранения объекта [IPresentation](../ipresentation/)). Может быть изменено через экземпляр [DocumentProperties](../documentproperties/), возвращаемый методом [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). См. пример в сводке метода [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Указывает, актуальны ли гиперссылки в документе. Установите элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите элемент в **false**, чтобы указать, что гиперссылки устарели. Читать **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Возвращает свойство менеджера. Читать [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Определяет общее количество звуковых или видеоклипов, присутствующих в документе. Только для чтения **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Возвращает имя приложения. Читать [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Определяет количество слайдов в презентации, содержащих заметки. Только для чтения **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Определяет общее количество абзацев, найденных в документе, если применимо. Только для чтения **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Возвращает целевой формат презентации. Читать [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Возвращает номер ревизии презентации. Читать **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Указывает режим отображения миниатюры документа. Установите элемент в **true**, чтобы включить масштабирование миниатюры документа к экрану. Установите элемент в **false**, чтобы включить обрезку миниатюры документа, показывая только те части, которые вписываются в экран. Читать **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Определяет, поделена ли презентация между несколькими людьми. Читать **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Определяет общее количество слайдов в документе презентации. Только для чтения **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Возвращает тему презентации. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Возвращает заголовок презентации. Читать [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Указывает заголовок каждой части документа. Эти части не являются частями документа, а концептуальными представлениями разделов документа. Только для чтения [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Общее время редактирования презентации. Читать [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Определяет общее количество слов, содержащихся в документе. Только для чтения **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Возвращает имя пользовательского свойства по указанному индексу. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Получает именованное булево значение из пользовательских свойств. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Получает именованное целочисленное значение из пользовательских свойств. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Получает именованное значение DateTime из пользовательских свойств. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Получает именованное строковое значение из пользовательских свойств. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Получает именованное значение float из пользовательских свойств. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Получает именованное значение double из пользовательских свойств. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Получает массив меток чувствительности из пользовательских свойств документа (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Возвращает пользовательское свойство, связанное с указанным именем. Читать [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Устанавливает пользовательское свойство, связанное с указанным именем. Записать [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Удаляет пользовательское свойство, связанное с указанным именем. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Устанавливает шаблон приложения. Записать [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Устанавливает автора презентации. Записать [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Устанавливает категорию презентации. Записать [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Устанавливает комментарии презентации. Записать [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Устанавливает свойство компании. Записать [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Устанавливает статус содержимого презентации. Записать [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Устанавливает тип содержимого презентации. Записать [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Возвращает дату создания презентации. Значения в UTC. Записать [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Устанавливает свойство документа HyperlinkBase. Записать [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Указывает, что одна или несколько гиперссылок в этой части были обновлены исключительно в этой части производителем. Следующий производитель, открывающий документ, должен обновить отношения гиперссылок новыми гиперссылками, указанными в этой части. Записать **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Устанавливает ключевые слова презентации. Записать [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Устанавливает дату последней печати презентации. Записать [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Устанавливает имя последнего человека, изменившего презентацию. Записать [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Возвращает дату последнего изменения презентации. Значения в UTC. Только для чтения в случае Presentation.DocumentProperties (поскольку будет обновляться внутренне во время процесса сохранения объекта [IPresentation](../ipresentation/)). Может быть изменено через экземпляр [DocumentProperties](../documentproperties/), возвращаемый методом [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). См. пример в сводке метода [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Указывает, актуальны ли гиперссылки в документе. Установите элемент в **true**, чтобы указать, что гиперссылки обновлены. Установите элемент в **false**, чтобы указать, что гиперссылки устарели. Записать **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Устанавливает свойство менеджера. Записать [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Устанавливает имя приложения. Записать [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Устанавливает целевой формат презентации. Записать [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Устанавливает номер ревизии презентации. Записать **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Указывает режим отображения миниатюры документа. Установите элемент в **true**, чтобы включить масштабирование миниатюры к экрану. Установите элемент в **false**, чтобы включить обрезку миниатюры, показывая только те части, которые вписываются в экран. Записать **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Определяет, поделена ли презентация между несколькими людьми. Записать **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Устанавливает тему презентации. Записать [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Устанавливает заголовок презентации. Записать [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Общее время редактирования презентации. Записать [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Устанавливает именованное булево пользовательское свойство. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Устанавливает именованное целочисленное пользовательское свойство. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Устанавливает именованное пользовательское свойство DateTime. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Устанавливает именованное строковое пользовательское свойство. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Устанавливает именованное пользовательское свойство float. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Устанавливает именованное пользовательское свойство double. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет конвертировать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)