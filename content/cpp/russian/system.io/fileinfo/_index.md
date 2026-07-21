---
title: FileInfo
second_title: Aspose.Slides для C++: справочник API
description: "Представляет путь к файлу и файл, на который указывает этот путь, и предоставляет методы для его манипулирования. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его функциям в качестве аргумента."
type: docs
weight: 274
url: /ru/system.io/fileinfo/
---
## FileInfo класс

Представляет путь к файлу и файл, на который указывает этот путь, и предоставляет методы для манипулирования им. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Открывает файл, представленный текущим объектом, для записи текста с использованием кодировки UTF-8 в режиме 'Append' без совместного доступа. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Копирует файл, представленный текущим объектом, в указанное место. Если файл назначения уже существует, копирование завершится неудачей. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Копирует файл, представленный текущим объектом, в указанное место. Параметр указывает, следует ли перезаписать существующий файл назначения. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Создаёт файл в месте, указанном путем, представляемым текущим объектом, и открывает его для чтения и записи в режиме обрезки без совместного доступа. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Создаёт файл в месте, указанном путем, представляемым текущим объектом, и открывает его для записи текста с кодировкой UTF-8 без совместного доступа. |
| void [Decrypt](./decrypt/)() | НЕ РЕАЛИЗОВАНО. |
| void [Delete](./delete/)() override | Удаляет файл, представленный текущим объектом. |
| void [Encrypt](./encrypt/)() | НЕ РЕАЛИЗОВАНО. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Создаёт новый экземпляр класса [FileInfo](./), представляющего указанный файл. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Не выполняет никаких действий. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Возвращает атрибуты сущности, представленной текущим объектом. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Возвращает время создания сущности, представленной текущим объектом, в локальном времени. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Возвращает время создания сущности, представленной текущим объектом, в UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Возвращает объект [DirectoryInfo](../directoryinfo/), представляющий каталог, в котором находится файл, представленный текущим объектом. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Возвращает полное имя каталога, в котором расположен файл, представленный текущим объектом. |
| **bool** [get_Exists](./get_exists/)() override | Возвращает значение, указывающее, существует ли файл. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Возвращает расширение файла, представленного текущим объектом. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Возвращает полное имя (включая путь) сущности, представленной текущим объектом. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Возвращает значение, указывающее, установлен ли атрибут ReadOnly. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Возвращает время последнего доступа к сущности, представленной текущим объектом, в локальном времени. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Возвращает время последнего доступа к сущности, представленной текущим объектом, в UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Возвращает время последней записи сущности, представленной текущим объектом, в локальном времени. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Возвращает время последней записи сущности, представленной текущим объектом, в UTC. |
| **int64_t** [get_Length](./get_length/)() | Возвращает размер файла в байтах. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Возвращает имя файла. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Перемещает файл, представленный текущим объектом, в указанное место. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Открывает файл, представленный текущим объектом, в указанном режиме для чтения и записи без совместного доступа. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и без совместного доступа. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и параметром совместного доступа. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Открывает файл, представленный текущим объектом, только для чтения в режиме 'Open' с совместным доступом для чтения. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Открывает существующий файл в месте, указанном путем, представляемым текущим объектом, для чтения текста с кодировкой UTF-8 без совместного доступа. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Открывает файл, представленный текущим объектом, только для записи в режиме 'OpenOrCreate' без совместного доступа. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типажа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [Refresh](../filesysteminfo/refresh/)() | Обновляет состояние текущего объекта. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Заменяет содержимое указанного файла назначения файлом, представленным текущим объектом [FileInfo](./), и создаёт резервную копию заменённого файла. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Заменяет содержимое указанного файла назначения файлом, представленным текущим объектом [FileInfo](./), и создаёт резервную копию заменённого файла. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Устанавливает указанные атрибуты для сущности, представленной текущим объектом. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Устанавливает время создания сущности, представленной текущим объектом, в локальном времени. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время создания сущности, представленной текущим объектом, в UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Устанавливает или снимает атрибут ReadOnly у файла. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, в локальном времени. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, в UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Устанавливает время последней записи сущности, представленной текущим объектом, в локальном времени. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время последней записи сущности, представленной текущим объектом, в UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых указателей. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Возвращает путь, представленный текущим объектом. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [FileSystemInfo](../filesysteminfo/)
* Пространство имён [System::IO](../)
* Library [Aspose.Slides](../../)