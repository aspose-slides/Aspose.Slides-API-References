---
title: IColorOperationCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของการแปลงสี
type: docs
url: /th/com.aspose.slides/icoloroperationcollection/
---
**ทั้งหมดที่ Implement อินเทอร์เฟซ:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

แสดงถึงคอลเลกชันของการแปลงสี

## วิธีการ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [add(int operation, float parameter)](#add-int-float-) | เพิ่มการดำเนินการใหม่ไปยังส่วนท้ายของคอลเลกชัน |
| [add(int operation)](#add-int-) | เพิ่มการดำเนินการใหม่ไปยังส่วนท้ายของคอลเลกชัน |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | แทรกการดำเนินการใหม่เข้าสู่คอลเลกชัน |
| [insert(int position, int operation)](#insert-int-int-) | แทรกการดำเนินการใหม่เข้าสู่คอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบการดำเนินการสีออกจากคอลเลกชัน |
| [clear()](#clear--) | ลบการดำเนินการสีทั้งหมด |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [IColorOperation](../../com.aspose.slides/icoloroperation).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [IColorOperation](../../com.aspose.slides/icoloroperation).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

เพิ่มการดำเนินการใหม่ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

เพิ่มการดำเนินการใหม่ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

แทรกการดำเนินการใหม่เข้าสู่คอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

แทรกการดำเนินการใหม่เข้าสู่คอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบการดำเนินการสีออกจากคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของการดำเนินการสีที่ต้องการลบ |

### clear() {#clear--}
```
public abstract void clear()
```

ลบการดำเนินการสีทั้งหมด.