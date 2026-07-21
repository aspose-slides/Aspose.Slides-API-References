---
title: Timing
second_title: Справочник API Aspose.Slides для C++
description: Представляет тайминг анимации.
type: docs
weight: 625
url: /ru/aspose.slides.animation/timing/
---
## Класс Timing

Represents animation timing.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **float** [get_Accelerate](./get_accelerate/)() override | Описывает процент продолжительности эффекта ускорения. Читает **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Описывает, будет ли анимация автоматически воспроизводиться в обратном направлении после воспроизведения в прямом направлении. Читает **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Описывает процент продолжительности эффекта замедления. Читает **float**. |
| **float** [get_Duration](./get_duration/)() override | Описывает длительность эффекта анимации. Читает **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Описывает количество повторений эффекта. Читает **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Описывает количество повторений эффекта. Читает **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читает **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Этот атрибут указывает, будет ли эффект повторяться до следующего клика. Читает **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Указывает, будет ли эффект перезапускаться после завершения. Читает [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Этот атрибут указывает, будет ли эффект перемотываться назад после завершения воспроизведения. Читает **bool**. |
| **float** [get_Speed](./get_speed/)() override | Указывает процент, на который следует ускорить (или замедлить) тайминг. Читает **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Описывает время задержки после триггера. Читает **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Описывает тип триггера. Читает [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Описывает процент продолжительности эффекта ускорения. Записывает **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Описывает, будет ли анимация автоматически воспроизводиться в обратном направлении после воспроизведения в прямом направлении. Записывает **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Описывает процент продолжительности эффекта замедления. Записывает **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Описывает длительность эффекта анимации. Записывает **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Описывает количество повторений эффекта. Записывает **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Описывает количество повторений эффекта. Записывает **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Записывает **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Этот атрибут указывает, будет ли эффект повторяться до следующего клика. Записывает **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Указывает, будет ли эффект перезапускаться после завершения. Записывает [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Этот атрибут указывает, будет ли эффект перемотываться назад после завершения воспроизведения. Записывает **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Указывает процент, на который следует ускорить (или замедлить) тайминг. Записывает **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Описывает время задержки после триггера. Записывает **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Описывает тип триггера. Записывает [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ITiming](../itiming/)
* Класс [IDOMObject](../../aspose.slides/idomobject/)
* Пространство имён [Aspose::Slides::Animation](../)
* Библиотека [Aspose.Slides](../../)