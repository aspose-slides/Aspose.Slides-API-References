---
title: IChartCellCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من الخلايا ذات البيانات.
type: docs
url: /ar/com.aspose.slides/ichartcellcollection/
---
**All Implemented Interfaces:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable  
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

يمثل مجموعة من الخلايا ذات البيانات.

## Methods

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | يعيد عنوان مجموعة الخلايا في المصنف. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | السلسلة المتصلة من قيم جميع الخلايا. |
| [get_Item(int index)](#get-Item-int-) | يعيد خلية (IChartDataCell) بناءً على الفهرس. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | إضافة خلية جديدة إلى المجموعة. |
| [add(Object value)](#add-java.lang.Object-) | ينشئ [IChartDataCell](../../com.aspose.slides/ichartdatacell) من القيمة المحددة ويضيفه إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل خلية من المجموعة بناءً على الفهرس. |
| [getCount()](#getCount--) | يحصل على عدد الخلايا في المجموعة. |

### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

يعيد عنوان مجموعة الخلايا في المصنف.

**Returns:**  
java.lang.String - العنوان لمجموعة الخلايا في المصنف String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

السلسلة المتصلة من قيم جميع الخلايا.

**Returns:**  
java.lang.String - السلسلة الناتجة String

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

يعيد خلية (IChartDataCell) بناءً على الفهرس.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس الخلية. |

**Returns:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - خلية ذات بيانات.

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

إضافة خلية جديدة إلى المجموعة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | خلية جديدة للإضافة. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

ينشئ [IChartDataCell](../../com.aspose.slides/ichartdatacell) من القيمة المحددة ويضيفه إلى المجموعة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | القيمة.

--------------------

تضيف هذه الطريقة ورقة عمل باسم AUTO_DATA وتضيف جميع القيم هناك. إذا استخدمت [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) لإضافة أو تعديل قيم الخلية، تأكد من عدم استخدام هذه الورقة. يجب ألا يتجاوز الحد الأقصى لعدد القيم المضافة باستخدام هذه الطريقة 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل خلية من المجموعة بناءً على الفهرس.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس الخلية المطلوب إزالتها. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد الخلايا في المجموعة. للقراءة فقط int.

**Returns:**  
int