---
title: IColorOperationCollection
second_title: Aspose.Slides for Java API 參考
description: 表示顏色變換操作的集合。
type: docs
url: /zh-hant/com.aspose.slides/icoloroperationcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

表示顏色變換操作的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回或設定指定索引處的操作。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 傳回或設定指定索引處的操作。 |
| [add(int operation, float parameter)](#add-int-float-) | 在集合的末端新增一個操作。 |
| [add(int operation)](#add-int-) | 在集合的末端新增一個操作。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 將新操作插入集合中。 |
| [insert(int position, int operation)](#insert-int-int-) | 將新操作插入集合中。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除顏色操作。 |
| [clear()](#clear--) | 移除所有顏色操作。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

傳回或設定指定索引處的操作。讀/寫 [IColorOperation](../../com.aspose.slides/icoloroperation)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**回傳值：**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

傳回或設定指定索引處的操作。讀/寫 [IColorOperation](../../com.aspose.slides/icoloroperation)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

在集合的末端新增一個操作。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| operation | int | 操作類型。 |
| parameter | float | 操作的參數。 |

**回傳值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 新增的操作。

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

在集合的末端新增一個操作。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| operation | int | 操作類型。 |

**回傳值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 新增的操作。

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

將新操作插入集合中。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作類型。 |
| parameter | float | 操作的參數。 |

**回傳值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 插入的操作。

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

將新操作插入集合中。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| position | int | 要插入操作的索引。 |
| operation | int | 操作類型。 |

**回傳值：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 插入的操作。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除顏色操作。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除的顏色操作的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除所有顏色操作。