---
title: DigitalSignatureCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร.
type: docs
url: /th/com.aspose.slides/digitalsignaturecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

แทนค่าคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าลายเซ็นตามดัชนี. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | เพิ่มลายเซ็นที่ส่วนท้ายของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลายเซ็นที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบลายเซ็นทั้งหมดจากคอลเลกชัน. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [size()](#size--) | คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการซิงโครไนซ์. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


คืนค่าลายเซ็นตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```


เพิ่มลายเซ็นที่ส่วนท้ายของคอลเลกชัน.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | ลายเซ็นที่จะเพิ่ม. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบลายเซ็นที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของลายเซ็นที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบลายเซ็นทั้งหมดจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากฐานการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |