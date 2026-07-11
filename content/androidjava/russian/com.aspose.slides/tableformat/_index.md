---
title: TableFormat
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет формат таблицы.
type: docs
url: /ru/com.aspose.slides/tableformat/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Представляет формат таблицы.
## Методы

| Метод | Описание |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Возвращает объект свойств заливки таблицы. |
| [getTransparency()](#getTransparency--) | Получает или задает прозрачность цвета заливки. |
| [setTransparency(float value)](#setTransparency-float-) | Получает или задает прозрачность цвета заливки. |
| [getEffective()](#getEffective--) | Получает действительные свойства форматирования таблицы с учётом наследования и применённых стилей таблицы. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Возвращает объект свойств заливки таблицы. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращает:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Возвращает:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Получает или задает прозрачность цвета заливки. Чтение/запись  float .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Получает действительные свойства форматирования таблицы с учётом наследования и применённых стилей таблицы.

--------------------

> ```
> Этот пример демонстрирует получение эффективного формата заливки для различных логических частей таблицы.
>  Обратите внимание, что форматирование ячеек всегда имеет более высокий приоритет, чем форматирование строк, строки - выше, чем столбцы, столбцы - выше, чем вся таблица.
>  Итак, свойства CellFormatEffectiveData в конечном итоге всегда используются для отрисовки таблицы. Следующий код — лишь пример использования API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Объект [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Версия. Только для чтения long.

**Возвращает:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Возвращает родительский IPresentationComponent. Только для чтения [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Возвращает:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)