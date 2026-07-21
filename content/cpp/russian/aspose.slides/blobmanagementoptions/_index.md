---
title: BlobManagementOptions
second_title: Справочник API Aspose.Slides для C++
description: Представляет параметры, которые можно использовать для управления правилами обработки BLOB и другими настройками BLOB.
type: docs
weight: 196
url: /ru/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions класс

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Методы

| Метод | Описание |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Создает новые параметры управления BLOB по умолчанию. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешений на создание файлов. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только после достижения этого ограничения применяются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти максимизирует производительность, но может привести к высокому использованию памяти. Используйте это свойство, чтобы адаптировать поведение к вашей среде или требованиям. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Это свойство определяет, может ли экземпляр класса [Presentation](../presentation/) быть владельцем источника — файла или потока — в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение срока жизни экземпляра [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться временный каталог [System](../../system/). Процесс-хост должен иметь разрешения на создание файлов и папок в этом месте. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Это свойство определяет, могут ли создаваться временные файлы при работе с BLOB, что существенно уменьшает потребление памяти, но требует разрешений на создание файлов. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Определяет максимальный общий размер (в байтах), который все BLOB могут занимать в памяти. По умолчанию все BLOB загружаются в память; только после достижения этого ограничения применяются альтернативные механизмы (например, временные файлы). Хранение BLOB в памяти максимизирует производительность, но может привести к высокому использованию памяти. Используйте это свойство, чтобы адаптировать поведение к вашей среде или требованиям. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Это свойство определяет, может ли экземпляр класса [Presentation](../presentation/) быть владельцем источника — файла или потока — в течение срока жизни экземпляра. Если экземпляр является владельцем, он блокирует источник. Это помогает улучшить потребление памяти и производительность при работе с BLOB, но источник (поток или файл) нельзя изменить в течение срока жизни экземпляра [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Корневой путь, где будут создаваться временные файлы. По умолчанию будет использоваться временный каталог [System](../../system/). Процесс-хост должен иметь разрешения на создание файлов и папок в этом месте. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IBlobManagementOptions](../iblobmanagementoptions/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)