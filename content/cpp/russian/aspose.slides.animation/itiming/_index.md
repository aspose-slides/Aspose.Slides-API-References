---
title: ITiming
second_title: Справочник API Aspose.Slides для C++
description: Представляет тайминг анимации.
type: docs
weight: 443
url: /ru/aspose.slides.animation/itiming/
---
## ITiming класс

Представляет тайминг анимации.

```cpp
class ITiming : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение плавающих точек в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение плавающих точек в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Определяет процент продолжительности эффекта ускорения. Читает **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Определяет, следует ли автоматически воспроизводить анимацию в обратном направлении после воспроизведения её вперёд. Читает **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Определяет процент продолжительности эффекта замедления. Читает **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Определяет продолжительность эффекта анимации. Читает **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Определяет количество повторений эффекта. Читает **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Определяет количество повторений эффекта. Читает **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читает **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Этот атрибут указывает, будет ли эффект повторяться до следующего клика. Читает **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Указывает, должен ли эффект перезапускаться после завершения. Читает [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Этот атрибут указывает, будет ли эффект перемотываться назад после воспроизведения. Читает **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Указывает процент ускорения (или замедления) тайминга. Читает **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Описывает задержку после срабатывания. Читает **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Описывает тип триггера. Читает [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует оператор C# lock() блокировки. Вызывается напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает общий счётчик ссылок на указанное значение. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Определяет процент продолжительности эффекта ускорения. Записывает **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Определяет, следует ли автоматически воспроизводить анимацию в обратном направлении после воспроизведения её вперёд. Записывает **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Определяет процент продолжительности эффекта замедления. Записывает **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Описывает продолжительность эффекта анимации. Записывает **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Описывает количество повторений эффекта. Записывает **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Описывает количество повторений эффекта. Записывает **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Записывает **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Этот атрибут указывает, будет ли эффект повторяться до следующего клика. Записывает **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Указывает, должен ли эффект перезапускаться после завершения. Записывает [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Этот атрибут указывает, будет ли эффект перемотываться назад после воспроизведения. Записывает **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Указывает процент ускорения (или замедления) тайминга. Записывает **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Описывает задержку после срабатывания. Записывает **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Описывает тип триггера. Записывает [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает общий счётчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует оператор C# lock() разблокировки. Вызывается напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides::Animation](../)
* Библиотека [Aspose.Slides](../../)