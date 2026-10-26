---
title: ICellCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một tập hợp các ô.
type: docs
url: /vi/com.aspose.slides/icellcollection/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Biểu diễn một tập hợp các ô.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về một ô theo vị trí của nó. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Trả về một ô theo vị trí của nó. Chỉ đọc [ICell](../../com.aspose.slides/icell).

--------------------

Một đối tượng CellEx có thể được trả về cho nhiều chỉ mục trong trường hợp ô được hợp nhất.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ICell](../../com.aspose.slides/icell)