---
title: ProtectionManager
second_title: Справочник API Aspose.Slides для C++
description: Управление защитой пароля презентации.
type: docs
weight: 4915
url: /ru/aspose.slides/protectionmanager/
---
## ProtectionManager класс


[Presentation](../presentation/) управление защитой пароля.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Определяет, защищена ли презентация паролем от изменения. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | Шифрует [Presentation](../presentation/) указанным паролем. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа-значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Чтение **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Получает пароль, используемый для шифрования презентации. Только для чтения [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Получает значение, указывающее, зашифровано ли данный экземпляр. Только для чтения **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла являются публичными. Значение true означает, что из зашифрованного файла презентации загружаются только свойства документа без использования пароля. Значение false означает, что загружается вся зашифрованная презентация с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, значение свойства всегда false. Если свойства документа зашифрованного файла не публичны, значение свойства всегда false. Если Presentation.EncryptDocumentProperties равно true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только для чтения **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Получает значение, указывающее, защищена ли эта презентация от записи. Только для чтения **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Получает рекомендацию только для чтения. Чтение **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa-значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [RemoveEncryption](./removeencryption/)() override | Удаляет шифрование. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Удаляет защиту от записи для этой презентации. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Это свойство имеет смысл, если презентация защищена паролем. Если true, то свойства документа зашифрованы в файле презентации. Если false, то свойства документа публичны, пока презентация зашифрована. Запись **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Устанавливает рекомендацию только для чтения. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Устанавливает защиту от записи для этой презентации с указанным паролем. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Класс [IProtectionManager](../iprotectionmanager/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)