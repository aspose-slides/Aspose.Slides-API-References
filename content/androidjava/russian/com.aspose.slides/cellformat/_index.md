---
title: CellFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет формат ячейки таблицы.
type: docs
url: /ru/com.aspose.slides/cellformat/
---
**Наследование:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**  
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)  
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Представляет формат ячейки таблицы.

## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Возвращает объект свойств заливки ячейки. |
| [getBorderLeft()](#getBorderLeft--) | Возвращает объект свойств линии левого края. |
| [getBorderTop()](#getBorderTop--) | Возвращает объект свойств линии верхнего края. |
| [getBorderRight()](#getBorderRight--) | Возвращает объект свойств линии правого края. |
| [getBorderBottom()](#getBorderBottom--) | Возвращает объект свойств линии нижнего края. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Возвращает объект свойств диагональной линии от верхнего левого к нижнему правому. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Возвращает объект свойств диагональной линии от нижнего левого к верхнему правому. |
| [getEffective()](#getEffective--) | Получает эффективные свойства форматирования ячейки таблицы с учётом наследования и применённых стилей таблицы. |
| [getTransparency()](#getTransparency--) | Получает или задаёт прозрачность цвета заливки. |
| [setTransparency(float value)](#setTransparency-float-) | Получает или задаёт прозрачность цвета заливки. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Версия. Только для чтения long.

**Возвращаемое значение:**  
long

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Возвращает объект свойств заливки ячейки. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Возвращает объект свойств линии левого края. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Возвращает объект свойств линии верхнего края. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Возвращает объект свойств линии правого края. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Возвращает объект свойств линии нижнего края. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Возвращает объект свойств диагональной линии от верхнего левого к нижнему правому. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Возвращает объект свойств диагональной линии от нижнего левого к верхнему правому. Только для чтения [ILineFormat](../../com.aspose.slides/ilineformat).

**Возвращаемое значение:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Получает эффективные свойства форматирования ячейки таблицы с учётом наследования и применённых стилей таблицы.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**  
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Объект [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Получает или задаёт прозрачность цвета заливки. Чтение/запись float.

**Возвращаемое значение:**  
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Получает или задаёт прозрачность цвета заливки. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |