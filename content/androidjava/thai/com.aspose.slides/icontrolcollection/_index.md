---
title: IControlCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คอลเลกชันของควบคุม ActiveX.
type: docs
url: /th/com.aspose.slides/icontrolcollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

คอลเลกชันของควบคุม ActiveX.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | ลบควบคุม ActiveX ออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบควบคุม ActiveX ที่เก็บไว้ในตำแหน่งที่ระบุจากคอลเลกชัน. |
| [clear()](#clear--) | ลบควบคุมทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าควบคุมที่ตำแหน่งที่ระบุ. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | สร้างและเพิ่มควบคุมใหม่ลงในคอลเลกชัน. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


ลบควบคุม ActiveX ออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | ควบคุมที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบควบคุม ActiveX ที่เก็บไว้ในตำแหน่งที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของควบคุมที่จะลบ. |

### clear() {#clear--}
```
public abstract void clear()
```


ลบควบคุมทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


คืนค่าควบคุมที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของควบคุม. |

**คืนค่า:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


สร้างและเพิ่มควบคุมใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| controlType | int | ประเภทของควบคุมที่จะเพิ่ม. |
| x | float | พิกัด X ของด้านซ้ายของกรอบรูปร่าง. |
| y | float | พิกัด Y ของด้านบนของกรอบรูปร่าง. |
| width | float | ความกว้างของกรอบรูปร่าง. |
| height | float | ความสูงของกรอบรูปร่าง. |

**คืนค่า:**
[IControl](../../com.aspose.slides/icontrol) - ควบคุมที่สร้าง [IControl](../../com.aspose.slides/icontrol).