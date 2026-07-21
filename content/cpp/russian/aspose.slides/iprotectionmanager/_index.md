---
title: IProtectionManager
second_title: Aspose.Slides для C++ справочник API
description: Управление защитой презентации паролем.
type: docs
weight: 3459
url: /ru/aspose.slides/iprotectionmanager/
---
## IProtectionManager класс

[Presentation](../presentation/) управление защитой паролем.

```cpp
class IProtectionManager : public virtual System::Object
```

## Методы

| Method | Описание |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | Определяет, защищена ли презентация паролем от изменения. |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | Шифрует [Presentation](../presentation/) указанным паролем. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа открыты, пока презентация зашифрована. Чтение **bool**. |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | Возвращает пароль шифрования. Только для чтения [System::String](../../system/string/). |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | Получает значение, указывающее, зашифровано ли данный экземпляр. Только для чтения **bool**. |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | Это свойство имеет смысл, если файл презентации защищен паролем, а свойства документа этого файла публичные. Значение true означает, что из зашифрованного файла презентации загружаются только свойства документа без использования пароля. Значение false означает, что вся зашифрованная презентация загружается с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, то значение свойства всегда false. Если свойства документа зашифрованного файла не публичны, то значение свойства всегда false. Если PresentationEx.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только для чтения **bool**. |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | Получает значение, указывающее, защищена ли эта презентация от записи. Только для чтения **bool**. |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | Получает рекомендацию только для чтения. Чтение **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [RemoveEncryption](./removeencryption/)() | Удаляет шифрование. |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | Убирает защиту от записи для этой презентации. |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа открыты, пока презентация зашифрована. Запись **bool**. |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | Устанавливает рекомендацию только для чтения. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счетчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имен [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)