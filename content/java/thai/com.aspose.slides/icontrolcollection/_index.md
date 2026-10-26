---
title: IControlCollection
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: คอลเลกชันของคอนโทรล ActiveX.
type: docs
url: /th/com.aspose.slides/icontrolcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

คอลเลกชันของคอนโทรล ActiveX.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | ลบคอนโทรล ActiveX ออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคอนโทรล ActiveX ที่จัดเก็บไว้ในตำแหน่งที่ระบุออกจากคอลเลกชัน |
| [clear()](#clear--) | ลบคอนโทรลทั้งหมดจากคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคอนโทรลที่ตำแหน่งที่ระบุ |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | สร้างและเพิ่มคอนโทรลใหม่ลงในคอลเลกชัน |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

ลบคอนโทรล ActiveX ออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | คอนโทรลที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบคอนโทรล ActiveX ที่จัดเก็บไว้ในตำแหน่งที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรลที่จะลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบคอนโทรลทั้งหมดจากคอลเลกชัน

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

คืนค่าคอนโทรลที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรล |

**ผลลัพธ์:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

สร้างและเพิ่มคอนโทรลใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| controlType | int | ประเภทของคอนโทรลที่จะเพิ่ม |
| x | float | ค่าพิกัด X ของด้านซ้ายของกรอบรูปร่าง |
| y | float | ค่าพิกัด Y ของด้านบนของกรอบรูปร่าง |
| width | float | ความกว้างของกรอบรูปร่าง |
| height | float | ความสูงของกรอบรูปร่าง |

**ผลลัพธ์:**
[IControl](../../com.aspose.slides/icontrol) - คอนโทรลที่สร้าง [IControl](../../com.aspose.slides/icontrol).