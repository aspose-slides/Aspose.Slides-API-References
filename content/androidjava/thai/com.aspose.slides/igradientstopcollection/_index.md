---
title: IGradientStopCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของ gradient stops.
type: docs
url: /th/com.aspose.slides/igradientstopcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

แสดงถึงคอลเลกชันของ gradient stops.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืน gradient stop ตามดัชนี. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบ gradient stop ที่ตำแหน่งดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบ gradient stop ทั้งหมดออกจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

ส่งคืน gradient stop ตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| color | java.lang.Integer | สีของ gradient stop ใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| presetColor | int | สีของ gradient stop ใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

สร้าง gradient stop ใหม่และเพิ่มไปยังตำแหน่งสุดท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| schemeColor | int | สีของ gradient stop ใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของ gradient stop ใหม่ในคอลเลกชัน.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| color | java.lang.Integer | สีของ gradient stop ใหม่. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| presetColor | int | สีของ gradient stop ใหม่. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

สร้าง gradient stop ใหม่และแทรกลงในคอลเลกชันที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่ gradient stop ใหม่จะถูกแทรก. |
| position | float | ตตำแหน่งของ gradient stop ใหม่. |
| schemeColor | int | สีของ gradient stop ใหม่. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบ gradient stop ที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของ gradient stop ที่ต้องการลบ. |

### clear() {#clear--}
```
public abstract void clear()
```

ลบ gradient stop ทั้งหมดออกจากคอลเลกชัน.