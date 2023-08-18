---
title: Table
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет таблицу на слайде.
type: docs
weight: 10050
url: /ru/aspose.slides/table/
---
## Table class

Представляет таблицу на слайде.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Возвращает набор столбцов. Только для чтения[`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов соединения на фигуре. Только для чтенияInt32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../ieffectformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Определяет, должен ли первый столбец таблицы отображаться со специальным форматированием. Чтение/записьBoolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Определяет, должна ли первая строка таблицы отображаться со специальным форматированием. Чтение/записьBoolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма фигуры. Чтение/запись[`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения[`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Определяет, должны ли четные строки отображаться с другим форматированием. Чтение/записьBoolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения[`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись[`IHyperlink`](../ihyperlink). |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только чтениеBoolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только чтениеBoolean. |
| [Item](../../aspose.slides/table/item) { get; } | Возвращает ячейку с указанными индексами столбца и строки. Только для чтения[`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Определяет, должен ли последний столбец таблицы отображаться со специальным форматированием. Чтение/записьBoolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Определяет, должна ли последняя строка таблицы отображаться со специальным форматированием. Чтение/записьBoolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя формы. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайдов. Только для чтенияUInt32. См. также[`UniqueId`](../shape/uniqueid)для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает ноль. Только для чтения[`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только чтение[`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанного фрейма формы. Чтение/запись[`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Определяет, имеет ли таблица порядок чтения справа налево. Чтение-записьBoolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle. |
| [Rows](../../aspose.slides/table/rows) { get; } | Возвращает набор строк. Только для чтения[`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения[`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Получает или устанавливает встроенный стиль таблицы. Чтение/запись[`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Возвращает объект TableFormat, содержащий свойства форматирования для этой таблицы. Только для чтения[`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который создает свойства 3D-эффекта для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32. См. также[`OfficeInteropShapeId`](../shape/officeinteropshapeid)для получения уникального идентификатора фигуры в области слайдов. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Определяет, должны ли четные столбцы отображаться с другим форматированием. Чтение/записьBoolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает положение фигуры в z-порядке. Shapes[0] возвращает форму в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает форму в начале z-порядка . Только для чтенияInt32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Возвращает миниатюру формы. ShapeThumbnailBounds.Тип границ эскиза фигуры Shape используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Объединяет соседние ячейки. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Устанавливает определенные свойства формата абзаца для всех абзацев ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Устанавливает определенные свойства формата части для всех частей ячеек таблицы. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Устанавливает определенные свойства формата текстового фрейма для всех текстовых фреймов ячеек таблицы. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое Shape как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое Shape как файл SVG. |

### Смотрите также

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
