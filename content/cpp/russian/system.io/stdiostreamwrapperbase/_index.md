---
title: STDIOStreamWrapperBase
second_title: Aspose.Slides для C++ справочник API
description: "Представляет базовый класс для обёрток, похожих на System.IO.Stream. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 352
url: /ru/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase класс

Представляет базовый класс для обёрток, похожих на [System.IO.Stream](../stream/). Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Методы

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию чтения. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию записи. |
| virtual void [Close](../stream/close/)() | Закрывает поток. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Копирует байты в указанный поток. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Копирует байты в указанный поток, используя указанный размер буфера. |
| void [Dispose](../stream/dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает поток. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ожидает завершения указанной асинхронной операции чтения. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| virtual void [Flush](../stream/flush/)() | Очищает буферы этого потока и записывает все буферизованные данные в базовое хранилище. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные записываться в базовое устройство, и отслеживает запросы на отмену. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Асинхронно очищает все буферы этого потока, заставляя любые буферизованные данные записываться в базовое устройство, и отслеживает запросы на отмену. |
| **bool** [get_CanRead](./get_canread/)() const override | Определяет, поддерживает ли поток чтение. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Получает значение, определяющее, может ли текущий поток завершиться по тайм-аууту. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Определяет, поддерживает ли поток запись. |
| **int64_t** [get_Length](./get_length/)() const override | Возвращает длину потока. |
| **int64_t** [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм-аута. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [STDIOStreamWrapperBase](./)\& [operator=](./operator_equal/)(const [STDIOStreamWrapperBase](./)\&) | Оператор копирующего присваивания. Удалён. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| virtual **int32_t** [Read](../stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Считывает указанное количество байт из потока и записывает их в указанный массив байт. |
| virtual **int32_t** [Read](../stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Считывает указанное количество байт из потока и записывает их в указанный массив байт. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Считывает указанное количество байт из потока и записывает их в указанный массив байт. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Считывает указанное количество байт из потока и записывает их в указанный диапазон байт. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно считывает последовательность байт из текущего потока, перемещает позицию в потоке на количество считанных байт и отслеживает запросы на отмену. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно считывает последовательность байт из текущего потока, перемещает позицию в потоке на количество считанных байт и отслеживает запросы на отмену. |
| virtual int [ReadByte](../stream/readbyte/)() | Считывает один байт из потока и возвращает 32-битное целочисленное значение, эквивалентное значению считанного байта. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/)) | Информация RTTI. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Устанавливает позицию потока, представленного текущим объектом. |
| void [set_Position](./set_position/)(**int64_t**) override | Устанавливает позицию потока. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Устанавливает значение, определяющее, может ли текущий поток завершиться по тайм-ауту. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| virtual void [SetLength](../stream/setlength/)(**int64_t**) | Устанавливает длину потока, представленного текущим объектом. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](./)\&) | Конструктор копирования. Удалён. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [Write](../stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Записывает указанный подпроизвольный диапазон байт из указанного массива байт в поток. |
| virtual void [Write](../stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Записывает указанный подпроизвольный диапазон байт из указанного массива байт в поток. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Записывает указанный подпроизвольный диапазон байт из указанного массива байт в поток. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Записывает указанный подпроизвольный диапазон байт из указанного диапазона байт в поток. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно записывает последовательность байт в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байт и отслеживает запросы на отмену. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно записывает последовательность байт в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байт и отслеживает запросы на отмену. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Записывает указанное беззнаковое 8-битное целое значение в поток. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Поток без базового хранилища. |

## Типы

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## См. также

* Класс [Stream](../stream/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)