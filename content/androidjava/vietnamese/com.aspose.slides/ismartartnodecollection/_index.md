---
title: ISmartArtNodeCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một tập hợp các nút SmartArt.
type: docs
url: /vi/com.aspose.slides/ismartartnodecollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Biểu diễn một tập hợp các nút SmartArt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nút theo chỉ mục. |
| [addNode()](#addNode--) | Thêm nút mới hoặc nút con. |
| [removeNode(int index)](#removeNode-int-) | Xóa nút hoặc nút con theo chỉ mục. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Xóa nút hoặc nút con. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Thêm nút mới ở vị trí đã chọn trong tập hợp các nút. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Trả về nút theo chỉ mục. Chỉ đọc [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục (bắt đầu từ 0) của phần tử. |

**Giá trị trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Thêm nút mới hoặc nút con.

**Giá trị trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nút đã thêm
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Xóa nút hoặc nút con theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của nút |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Xóa nút hoặc nút con.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nút cần xóa. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Thêm nút mới ở vị trí đã chọn trong tập hợp các nút.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Vị trí nút (bắt đầu từ 0). |

**Giá trị trả về:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nút đã thêm