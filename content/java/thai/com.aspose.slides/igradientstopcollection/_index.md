---
title: IGradientStopCollection
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นคอลเลกชันของจุดหยุดไล่สี.
type: docs
url: /th/com.aspose.slides/igradientstopcollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

เป็นคอลเลกชันของจุดหยุดไล่สี.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดหยุดไล่สีตามดัชนี. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบจุดหยุดไล่สีที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบจุดหยุดไล่สีทั้งหมดจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


คืนค่าจุดหยุดไล่สีตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```


สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| color | java.awt.Color | สีของจุดหยุดไล่สีใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของจุดหยุดไล่สีใหม่ในคอลเลกชัน.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| presetColor | int | สีของจุดหยุดไล่สีใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของจุดหยุดไล่สีใหม่ในคอลเลกชัน.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


สร้างจุดหยุดไล่สีใหม่และเพิ่มไปยังท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| schemeColor | int | สีของจุดหยุดไล่สีใหม่. |

**ค่าที่ส่งคืน:**
[IGradientStop](../../com.aspose.slides/igradientstop) - ดัชนีของจุดหยุดไล่สีใหม่ในคอลเลกชัน.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```


สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่จุดหยุดไล่สีใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| color | java.awt.Color | สีของจุดหยุดไล่สีใหม่. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่จุดหยุดไล่สีใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| presetColor | int | สีของจุดหยุดไล่สีใหม่. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


สร้างจุดหยุดไล่สีใหม่และแทรกลงในคอลเลกชันที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีในคอลเลกชันที่จุดหยุดไล่สีใหม่จะถูกแทรก. |
| position | float | ตำแหน่งของจุดหยุดไล่สีใหม่. |
| schemeColor | int | สีของจุดหยุดไล่สีใหม่. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบจุดหยุดไล่สีที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของจุดหยุดไล่สีที่ต้องการลบ. |

### clear() {#clear--}
```
public abstract void clear()
```


ลบจุดหยุดไล่สีทั้งหมดจากคอลเลกชัน.