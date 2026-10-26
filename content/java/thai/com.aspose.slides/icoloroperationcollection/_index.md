---
title: IColorOperationCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของการดำเนินการแปลงสี
type: docs
url: /th/com.aspose.slides/icoloroperationcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

เป็นคอลเลกชันของการดำเนินการแปลงสี
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่า หรือ ตั้งค่าการดำเนินการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | คืนค่า หรือ ตั้งค่าการดำเนินการที่ตำแหน่งที่ระบุ |
| [add(int operation, float parameter)](#add-int-float-) | เพิ่มการดำเนินการใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [add(int operation)](#add-int-) | เพิ่มการดำเนินการใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | แทรกการดำเนินการใหม่เข้าไปในคอลเลกชัน |
| [insert(int position, int operation)](#insert-int-int-) | แทรกการดำเนินการใหม่เข้าไปในคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบการดำเนินการสีออกจากคอลเลกชัน |
| [clear()](#clear--) | ลบการดำเนินการสีทั้งหมด |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

คืนค่า หรือ ตั้งค่าการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [IColorOperation](../../com.aspose.slides/icoloroperation).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

คืนค่า หรือ ตั้งค่าการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [IColorOperation](../../com.aspose.slides/icoloroperation).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

เพิ่มการดำเนินการใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

เพิ่มการดำเนินการใหม่ไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

แทรกการดำเนินการใหม่เข้าไปในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| position | int | ตำแหน่งที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

แทรกการดำเนินการใหม่เข้าไปในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| position | int | ตำแหน่งที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบการดำเนินการสีออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของการดำเนินการสีที่ต้องการลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบการดำเนินการสีทั้งหมด.