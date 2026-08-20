---
title: IColorOperationCollection
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من عمليات تحويل اللون.
type: docs
url: /ar/com.aspose.slides/icoloroperationcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

يمثل مجموعة من عمليات تحويل اللون.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع أو تعيين العملية في الفهرس المحدد. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | إرجاع أو تعيين العملية في الفهرس المحدد. |
| [add(int operation, float parameter)](#add-int-float-) | يضيف عملية جديدة إلى نهاية المجموعة. |
| [add(int operation)](#add-int-) | يضيف عملية جديدة إلى نهاية المجموعة. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | يدرج العملية الجديدة في مجموعة. |
| [insert(int position, int operation)](#insert-int-int-) | يدرج العملية الجديدة في مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عملية اللون من مجموعة. |
| [clear()](#clear--) | يزيل جميع عمليات اللون. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

إرجاع أو تعيين العملية في الفهرس المحدد. قراءة/كتابة [IColorOperation](../../com.aspose.slides/icoloroperation).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

إرجاع أو تعيين العملية في الفهرس المحدد. قراءة/كتابة [IColorOperation](../../com.aspose.slides/icoloroperation).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

يضيف عملية جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |
| parameter | float | معامل العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المضافة.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

يضيف عملية جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operation | int | نوع العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المضافة.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

يدرج العملية الجديدة في مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي سيتم إدراج العملية عنده. |
| operation | int | نوع العملية. |
| parameter | float | معامل العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المدخلة.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

يدرج العملية الجديدة في مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | int | الفهرس الذي سيتم إدراج العملية عنده. |
| operation | int | نوع العملية. |

**القيمة المرجعة:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - العملية المدخلة.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل عملية اللون من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس عملية اللون التي يجب إزالتها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع عمليات اللون.