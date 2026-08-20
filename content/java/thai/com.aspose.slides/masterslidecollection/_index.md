---
title: MasterSlideCollection
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของมาสเตอร์สไลด์.
type: docs
url: /th/com.aspose.slides/masterslidecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)  
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Represents a collection of master slides.  
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Removes unused master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified master slide to the end of the collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserts a copy of a specified master slide to specified position of the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

รับจำนวนองค์ประกอบที่อยู่ในคอลเลกชันจริง ๆ อ่านอย่างเดียว int.

**Returns:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [MasterSlide](../../com.aspose.slides/masterslide).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

ลบการพบครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเลกชัน

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | The master slide to remove from the collection. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุในคอลเลกชัน

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove.

--------------------

เพื่อหลีกเลี่ยงการโยงข้อผิดพลาด PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของมาสเตอร์ก่อน. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

ลบมาสเตอร์สไลด์ที่ไม่ได้ใช้

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Determines, whether this method should remove unused master even if its [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) property is set to true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

เพิ่มสำเนาของมาสเตอร์สไลด์ที่ระบุไปยังตำแหน่งสุดท้ายของคอลเลกชัน สไลด์การจัดวางที่เชื่อมโยงจะถูกคัดลอกด้วย

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide to clone. |

**Returns:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - Added slide.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

แทรกสำเนาของมาสเตอร์สไลด์ที่ระบุไปยังตำแหน่งที่ระบุของคอลเลกชัน สไลด์การจัดวางที่เชื่อมโยงจะถูกคัดลอกด้วย

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation เพื่อโหลดไฟล์การนำเสนอต้นทาง
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // สร้างอินสแตนซ์ของคลาส Presentation สำหรับการนำเสนอปลายทาง (ที่สไลด์จะถูกคัดลอก)
>      Presentation destPres = new Presentation();
>      try {
>          // สร้างอินสแตนซ์ ISlide จากคอลเลกชันของสไลด์ในการนำเสนอต้นทางพร้อมกับ
>          // มาสเตอร์สไลด์
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // ดึงมาสเตอร์สไลด์ของการนำเสนอปลายทาง
>          IMasterSlideCollection masters = destPres.getMasters();
>          // คัดลอกมาสเตอร์สไลด์ที่ต้องการจากการนำเสนอต้นทางไปยังคอลเลกชันของมาสเตอร์ใน
>          // การนำเสนอปลายทาง
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // คอลเลกชันของสไลด์ในการนำเสนอปลายทาง
>          ISlideCollection slds = destPres.getSlides();
>          // คัดลอกสไลด์ต้นทางไปยังคอลเลกชันสไลด์ปลายทาง.
>          slds.addClone(SourceSlide, iSlide, true);
>          // บันทึกการนำเสนอปลายทางไปยังดิสก์
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of new slide. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slide to clone. |

**Returns:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - Inserted master slide.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**Returns:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากฐานการซิงโครไนซ์ อ่านอย่างเดียว Object.

**Returns:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด