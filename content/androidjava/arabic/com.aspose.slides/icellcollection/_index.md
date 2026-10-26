---
title: ICellCollection
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل مجموعة من الخلايا.
type: docs
url: /ar/com.aspose.slides/icellcollection/
---
**كل الواجهات المُنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

يمثل مجموعة من الخلايا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد خلية حسب موقعها. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


يعيد خلية حسب موقعها. قراءة فقط [ICell](../../com.aspose.slides/icell).

--------------------

يمكن إرجاع كائن CellEx واحد لعدة مؤشرات في حال تم دمج الخلية.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell)