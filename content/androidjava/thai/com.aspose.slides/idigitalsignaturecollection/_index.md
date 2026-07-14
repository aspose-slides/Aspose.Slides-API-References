---
title: IDigitalSignatureCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร
type: docs
url: /th/com.aspose.slides/idigitalsignaturecollection/
---
**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

เป็นคอลเลกชันของลายเซ็นดิจิทัลที่แนบกับเอกสาร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนลายเซ็นตามดัชนี. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | เพิ่มลายเซ็นที่ส่วนท้ายของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลายเซ็นที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบลายเซ็นทั้งหมดออกจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


ส่งคืนลายเซ็นตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | ลายเซ็นที่จะเพิ่ม. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบลายเซ็นที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของลายเซ็นที่ต้องการลบ. |

### clear() {#clear--}
```
public abstract void clear()
```


ลบลายเซ็นทั้งหมดออกจากคอลเลกชัน.