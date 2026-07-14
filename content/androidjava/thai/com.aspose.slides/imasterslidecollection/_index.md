---
title: IMasterSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงถึงคอลเลกชันของสไลด์แม่แบบ.
type: docs
url: /th/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**  
คอลเลกชันของอินเทอร์เฟซที่ใช้งานทั้งหมด:
com.aspose.slides.IGenericCollection  
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Represents a collection of master slides.  
แสดงถึงคอลเลกชันของสไลด์แม่แบบ.

## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลีเมนต์ที่ตำแหน่งที่ระบุ. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | ลบการพบครั้งแรกของอ็อบเจกต์ที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบอิลีเมนต์ที่ตำแหน่งที่ระบุของคอลเลกชัน. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | ลบสไลด์แม่แบบที่ไม่ได้ใช้. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | เพิ่มสำเนาของสไลด์แม่แบบที่ระบุไปยังท้ายของคอลเลกชัน. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | แทรกสำเนาของสไลด์แม่แบบที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

ดึงอิลีเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IMasterSlide](../../com.aspose.slides/imasterslide).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide)

### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

ลบการพบครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์แม่แบบที่จะลบออกจากคอลเลกชัน. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบอิลีเมนต์ที่ตำแหน่งที่ระบุของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของอิลีเมนต์ที่ต้องการลบ. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

ลบสไลด์แม่แบบที่ไม่ได้ใช้.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | กำหนดว่าควรลบสไลด์แม่แบบที่ไม่ได้ใช้หรือไม่ แม้ว่า property [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) ของมันจะตั้งค่าเป็น true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

เพิ่มสำเนาของสไลด์แม่แบบที่ระบุไปยังท้ายของคอลเลกชัน ทั้งสไลด์เลย์เอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่จะทำการคัดลอก. |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์ที่เพิ่ม.

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

แทรกสำเนาของสไลด์แม่แบบที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน ทั้งสไลด์เลย์เอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วย.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของสไลด์ใหม่. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | สไลด์ที่จะทำการคัดลอก. |

**ผลลัพธ์:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - สไลด์แม่แบบที่แทรก.