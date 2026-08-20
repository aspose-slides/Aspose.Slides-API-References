---
title: DigitalSignatureCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนความเป็นคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร
type: docs
url: /th/com.aspose.slides/digitalsignaturecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)  
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

แทนความเป็นคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร

## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนลายเซ็นตามดัชนี |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | เพิ่มลายเซ็นที่ท้ายคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบลายเซ็นที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบลายเซ็นทั้งหมดจากคอลเลกชัน |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [size()](#size--) | ส่งคืนจำนวนของสมาชิกในคอลเลกชัน |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบประสาน (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการประสาน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกสมาชิกทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |

### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

ส่งคืนลายเซ็นตามดัชนี

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)

### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

เพิ่มลายเซ็นที่ท้ายคอลเลกชัน

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | ลายเซ็นที่จะเพิ่ม |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบลายเซ็นที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของลายเซ็นที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบลายเซ็นทั้งหมดจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

ส่งคืน enumerator ที่วนผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - IGenericEnumerator ที่สามารถใช้ในการวนผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนของสมาชิกในคอลเลกชัน. อ่านอย่างเดียว int.

**Returns:**
int

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบประสาน (thread-safe). อ่านอย่างเดียว boolean.

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการประสาน. อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกสมาชิกทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |