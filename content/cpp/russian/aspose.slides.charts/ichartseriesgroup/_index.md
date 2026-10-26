---
title: IChartSeriesGroup
second_title: Справочник API Aspose.Slides для C++
description: Представляет группу серий.
type: docs
weight: 846
url: /ru/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup класс


Представляет группу серий.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Указывает, как значения размеров пузырьков отображаются на диаграмме пузырей. Чтение [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Указывает коэффициент масштабирования для диаграммы пузырей (может быть от 0 до 300 процентов от размера по умолчанию). Чтение **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Возвращает диаграмму. Только для чтения [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Возвращает серию диаграммы в группе по указанному индексу. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Чтение **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Получает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней точки, от 0 до 360 градусов). Чтение **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Возвращает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Чтение **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Чтение **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Истина, если у диаграммы есть линии серии. Применяется к сложенным столбчатым и OfPie диаграммам. Чтение **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Указывает формат HiLowLines. HiLowLines применяется с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме пирог-из-пирога или столбец-из-пирога. Чтение [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Информация о пользовательском разбиении для диаграммы пирог-из-пирога или столбец-из-пирога с пользовательским разбиением. Возвращает точку данных, которая должна быть отрисована во втором круге или столбце по индексу. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Информация о пользовательском разбиении для диаграммы пирог-из-пирога или столбец-из-пирога с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором круге или столбце. Только для чтения [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце в диаграмме пирог-из-пирога или столбец-из-пирога. Используется вместе со свойством PieSplitBy. Чтение **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Указывает, построена ли серия этой группы на дополнительной оси. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Возвращает презентацию. Только для чтения [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Указывает размер второго круга или столбца в диаграмме пирог-из-пирога или столбец-из-пирога в процентах от первого круга (может быть от 5 до 200 процентов). Чтение **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Обеспечивает доступ к верхним/нижним полосам линейной или сточной диаграммы. Только для чтения [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Получает элемент по указанному индексу. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывать напрямую или использовать объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет выполнять копирующее построение подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет выполнять копирующее построение подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Указывает, как значения размеров пузырьков отображаются на диаграмме пузырей. Запись [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Указывает коэффициент масштабирования для диаграммы пузырей (может быть от 0 до 300 процентов от размера по умолчанию). Запись **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Запись **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Устанавливает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней точки, от 0 до 360 градусов). Запись **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Устанавливает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Запись **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Запись **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Истина, если у диаграммы есть линии серии. Применяется к сложенным столбчатым и OfPie диаграммам. Запись **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Указывает, что каждый маркер данных в серии имеет разный цвет. Запись **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Указывает, как определить, какие точки находятся во втором круге или столбце в диаграмме пирог-из-пирога или столбец-из-пирога. Запись [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Указывает значение, которое используется для определения, какие точки находятся во втором круге или столбце в диаграмме пирог-из-пирога или столбец-из-пирога. Запись **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Указывает размер второго круга или столбца в диаграмме пирог-из-пирога или столбец-из-пирога в процентах от первого круга (может быть от 5 до 200 процентов). Запись **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокирование оператора C# lock(). Вызывать напрямую или использовать объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе [ChartSeriesGroup](../chartseriesgroup/) являются чтением/записью. Каждое из "свойств группы серий" может иметь только для чтения проекцию в классе [ChartSeries](../chartseries/).

## См. также

* Класс [IChartComponent](../ichartcomponent/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)