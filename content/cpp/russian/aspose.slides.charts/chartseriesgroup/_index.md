---
title: ChartSeriesGroup
second_title: Справка API Aspose.Slides для C++
description: Представляет группу серий.
type: docs
weight: 300
url: /ru/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup класс

Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Указывает, как значения размеров пузырей представлены на пузырчатой диаграмме. Читать [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Указывает коэффициент масштаба для пузырчатой диаграммы (может быть от 0 до 300 % от размера по умолчанию). Читать **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Возвращает родительскую диаграмму. Только для чтения [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Возвращает серию диаграммы в группе по указанному индексу. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 % от размера области построения). Читать **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Получает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 градусов). Читать **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Возвращает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Читать **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Читать **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Истина, если у диаграммы есть линии серий. Применяется к сложенным столбчатым и OfPie диаграммам. Читать **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Задает формат HiLowLines. HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Указывает, что каждый маркер данных в серии имеет разный цвет. Читать **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie. Читать [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Пользовательская информация разбиения для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Возвращает точку данных, которая должна быть отрисована во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie по индексу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Пользовательская информация разбиения для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie. Только для чтения [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Читать **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Указывает, отображаются ли серии этой группы на вторичной оси. Только для чтения **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 %). Читать **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Возвращает коллекцию серий. Только для чтения [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Возвращает тип этой группы серий. Только для чтения [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Обеспечивает доступ к верхним/нижним столбцам линейной или биржевой диаграммы. Только для чтения [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Получает элемент по указанному индексу. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Указывает, как значения размеров пузырей представлены на пузырчатой диаграмме. Записать [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Указывает коэффициент масштаба для пузырчатой диаграммы (может быть от 0 до 300 % от размера по умолчанию). Записать **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 % от размера области построения). Записать **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Устанавливает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 градусов). Записать **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Устанавливает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Записать **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Записать **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Истина, если у диаграммы есть линии серий. Применяется к сложенным столбчатым и OfPie диаграммам. Записать **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Указывает, что каждый маркер данных в серии имеет разный цвет. Записать **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Указывает, насколько столбцы и колонки перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Указывает, как определить, какие точки данных находятся во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie. Записать [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или столбце в диаграмме pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Записать **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Указывает размер второго круга или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 %). Записать **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Замечания

1) Смотрите сводку и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе ("series group properties"). "Series group properties" в классе [ChartSeriesGroup](./) имеют режим чтение/запись. Каждое из "series group properties" может иметь проекцию только для чтения в классе [ChartSeries](../chartseries/).

## См. также

* Класс [IChartSeriesGroup](../ichartseriesgroup/)
* Класс [IDOMObject](../../aspose.slides/idomobject/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)