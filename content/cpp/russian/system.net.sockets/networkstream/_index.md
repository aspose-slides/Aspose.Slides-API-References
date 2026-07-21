---
title: NetworkStream
second_title: "Aspose.Slides для C++ справка API"
description: "Обеспечивает базовый поток данных для сетевого доступа. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи в функции в качестве аргумента."
type: docs
weight: 40
url: /ru/system.net.sockets/networkstream/
---
## NetworkStream класс

Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## Методы

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Инициирует асинхронную операцию чтения. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию чтения. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Инициирует асинхронную операцию записи. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию записи. |
| void [Close](./close/)(int) | Закрывает текущий экземпляр после истечения указанного времени. |
| virtual void [Close](../../system.io/stream/close/)() | Закрывает поток. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Копирует байты в указанный поток. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Копирует байты в указанный поток, используя указанный размер буфера. |
| void [Dispose](../../system.io/stream/dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает поток. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Ожидает завершения указанной асинхронной операции чтения. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ожидает завершения указанной асинхронной операции чтения. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| void [Flush](./flush/)() override | Очищает буферы этого потока и записывает все буферизованные данные в нижележащее хранилище. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные быть записанными в нижележащее устройство и отслеживает запросы отмены. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные быть записанными в нижележащее устройство и отслеживает запросы отмены. |
| **bool** [get_CanRead](./get_canread/)() const override | Определяет, читаем ли поток. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Получает значение, определяющее, может ли текущий поток завершить работу по тайм-аууту. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Определяет, доступна ли запись в поток. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Возвращает значение, указывающее, есть ли доступные данные для чтения. |
| **int64_t** [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| **int64_t** [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Получает нижележащий [Socket](../socket/). |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм-аута. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Создает новый экземпляр. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Создает новый экземпляр. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Создает новый экземпляр. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Читает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Читает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Читает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Читает указанное количество байтов из потока и записывает их в указанный диапазон байтов. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно читает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы отмены. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно читает последовательность байтов из текущего потока, перемещает позицию в потоке на количество прочитанных байтов и отслеживает запросы отмены. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Читает один байт из потока и возвращает 32-разрядное целое значение, эквивалентное значению прочитанного байта. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Устанавливает позицию потока, представленного текущим объектом. |
| void [set_Position](./set_position/)(**int64_t**) override | Устанавливает позицию потока. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Устанавливает значение, определяющее, может ли текущий поток завершить работу по тайм-ауту. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Устанавливает значение, определяющее, может ли текущий поток завершить работу по тайм-ауту. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| void [SetLength](./setlength/)(**int64_t**) override | Устанавливает длину потока, представленного текущим объектом. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Записывает указанный подпассив байтов из заданного массива байтов в поток. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Записывает указанный подпассив байтов из заданного массива байтов в поток. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Записывает указанный подпассив байтов из заданного массива байтов в поток. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Записывает указанный подпассив байтов из указанного диапазона байтов в поток. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Записывает указанное беззнаковое 8-битное целое значение в поток. |
| virtual  [~NetworkStream](./~networkstream/)() | Разрушает текущий экземпляр. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Поток без нижележащего хранилища. |

## См. также

* Класс [Stream](../../system.io/stream/)
* Пространство имен [System::Net::Sockets](../)
* Библиотека [Aspose.Slides](../../)