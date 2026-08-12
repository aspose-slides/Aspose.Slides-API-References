---
title: Add()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เพิ่มลายเซ็นที่ส่วนท้ายของคอลเลกชัน.
type: docs
weight: 53
url: /th/aspose.slides/digitalsignaturecollection/add/
---
## DigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) เมธอด

เพิ่มลายเซ็นที่ส่วนท้ายของคอลเลกชัน

```cpp
void Aspose::Slides::DigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> signature) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| signature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | ลายเซ็นที่จะเพิ่ม |

## หมายเหตุ

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IDigitalSignature](../../idigitalsignature/)
* คลาส [DigitalSignatureCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)