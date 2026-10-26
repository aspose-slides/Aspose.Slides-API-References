---
title: ICellCollection
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من الخلايا.
type: docs
url: /ar/com.aspose.slides/icellcollection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

يمثل مجموعة من الخلايا.
## الطرق

| طريقة | وصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع خلية وفق موقعها. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

يرجع خلية وفق موقعها. للقراءة فقط [ICell](../../com.aspose.slides/icell).

--------------------

يمكن إرجاع كائن CellEx واحد لعدة مؤشرات في حالة دمج الخلية.

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell)