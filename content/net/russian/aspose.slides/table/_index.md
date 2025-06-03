---
title: Table
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет таблицу на слайде.
type: docs
weight: 10550
url: /ru/aspose.slides/table/
---

## Класс Table

Представляет таблицу на слайде.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Возвращает коллекцию колонок. Только для чтения [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Возвращает объект TableFormat.FillFormat, содержащий формат заливки для таблицы. Только для чтения [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Определяет, нужно ли рисовать первый столбец таблицы с особым форматированием. Чтение/запись Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Определяет, нужно ли рисовать первую строку таблицы с особым форматированием. Чтение/запись Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает замки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Определяет, должны ли четные строки рисоваться с другим форматированием. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определяемую при клике мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определяемую при наведении мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает параметр "Пометить как декоративный" Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Возвращает ячейку по указанным индексам столбца и строки. Только для чтения [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Определяет, должен ли последний столбец таблицы быть нарисован с особым форматированием. Чтение/запись Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Определяет, должна ли последняя строка таблицы быть нарисована с особым форматированием. Чтение/запись Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств линий. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Не должно быть null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в контексте слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в контексте презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнители для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства сырой рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Определяет, имеет ли таблица порядок чтения справа налево. Чтение/запись Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое фигура вращается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Возвращает коллекцию строк. Только для чтения [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает замки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Получает или устанавливает встроенный стиль таблицы. Чтение/запись [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Возвращает объект TableFormat, который содержит свойства форматирования для этой таблицы. Только для чтения [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства эффектов 3D для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств 3D. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в контексте презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в контексте слайда. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Определяет, должны ли четные столбцы рисоваться с другим форматированием. Чтение/запись Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату X верхнего левого угла фигуры. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату Y верхнего левого угла фигуры. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке Z. Shapes[0] возвращает фигуру на заднем плане, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или главного слайда, от которой унаследована текущая фигура). Возвращается null, если текущая фигура не унаследована. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Объединяет соседние ячейки. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Устанавливает заданные свойства форматирования абзаца для всех абзацев ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Устанавливает заданные свойства форматирования частей для всех частей ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Устанавливает заданные свойства форматирования текстового фрейма для всех текстовых фреймов ячеек таблицы. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в виде файла SVG. |

### Смотрите также

* класс [GraphicalObject](../graphicalobject)
* интерфейс [ITable](../itable)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->