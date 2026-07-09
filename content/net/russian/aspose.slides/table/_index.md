---
title: Table
second_title: Aspose.Sildes для .NET справочник API
description: Представляет таблицу на слайде.
type: docs
weight: 10860
url: /ru/aspose.slides/table/
---
## Table класс

Представляет таблицу на слайде.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задаёт альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задаёт заголовок альтернативного текста, связанный с фигурой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в чёрно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Возвращает коллекцию столбцов. Только для чтения [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффекта. Только для чтения [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Возвращает объект TableFormat.FillFormat, содержащий параметры заливки для таблицы. Только для чтения [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Определяет, следует ли отрисовывать первый столбец таблицы со специальным форматированием. Чтение/запись Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Определяет, следует ли отрисовывать первую строку таблицы со специальным форматированием. Чтение/запись Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задаёт свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задаёт высоту фигуры в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Определяет, следует ли отрисовывать чётные строки с другим форматированием. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задаёт гиперссылку, определённую для щелчка мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задаёт гиперссылку, определённую для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Возвращает или задаёт параметр 'Отметить как декоративный'. Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Возвращает ячейку по указанным индексам столбца и строки. Только для чтения [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Определяет, следует ли отрисовывать последний столбец таблицы со специальным форматированием. Чтение/запись Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Определяет, следует ли отрисовывать последнюю строку таблицы со специальным форматированием. Чтение/запись Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задаёт имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор в пределах слайда, сохраняющийся на протяжении жизни фигуры и позволяющий PowerPoint или коду interop надёжно ссылаться на фигуру из любого места документа. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает объект родительской GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель (placeholder) для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задаёт свойства сырой рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Определяет, имеет ли таблица порядок чтения справа налево. Чтение/запись Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задаёт количество градусов, на которое указанная фигура вращается вокруг оси z. Положительное значение означает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Возвращает коллекцию строк. Только для чтения [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Возвращает или задаёт встроенный стиль таблицы. Чтение/запись [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Возвращает объект TableFormat, содержащий свойства форматирования этой таблицы. Только для чтения [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3D-свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Определяет, следует ли отрисовывать чётные столбцы с другим форматированием. Чтение/запись Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задаёт ширину фигуры в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задаёт координату x верхнего левого угла фигуры в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задаёт координату y верхнего левого угла фигуры в пунктах. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в Z-порядке. Shapes[0] возвращает фигуру в задней части Z-порядка, а Shapes[Shapes.Count - 1] — фигуру в передней части Z-порядка. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму заполнителя (фигуру из макета и/или шаблона слайда, от которой наследуется текущая фигура). Возвращает null, если текущая фигура не наследуется. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Объединяет соседние ячейки. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Устанавливает заданные свойства формата абзаца для всех абзацев ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Устанавливает заданные свойства формата части для всех частей ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Устанавливает заданные свойства формата текстовой рамки для всех текстовых рамок ячеек таблицы. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое Shape как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое Shape как файл SVG. |

### См. также

* класс [GraphicalObject](../graphicalobject)
* интерфейс [ITable](../itable)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->