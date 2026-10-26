---
title: ISmartArtNodeCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของโหนด SmartArt.
type: docs
url: /th/com.aspose.slides/ismartartnodecollection/
---
**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

เป็นคอลเลกชันของโหนด SmartArt.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าโหนดตามดัชนี. |
| [addNode()](#addNode--) | เพิ่มโหนดใหม่หรือโหนดย่อย. |
| [removeNode(int index)](#removeNode-int-) | ลบโหนดหรือโหนดย่อยตามดัชนี. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | ลบโหนดหรือโหนดย่อย. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

คืนค่าโหนดตามดัชนี. อ่านอย่างเดียว [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานของอิลิเมนต์. |

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

เพิ่มโหนดใหม่หรือโหนดย่อย.

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

ลบโหนดหรือโหนดย่อยตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีศูนย์ฐานของโหนด |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

ลบโหนดหรือโหนดย่อย.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | โหนดที่ต้องการลบ. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

เพิ่มโหนดใหม่ในตำแหน่งที่เลือกของคอลเลกชันโหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| position | int | ตำแหน่งโหนดเริ่มจากศูนย์. |

**คืนค่า:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - โหนดที่เพิ่ม