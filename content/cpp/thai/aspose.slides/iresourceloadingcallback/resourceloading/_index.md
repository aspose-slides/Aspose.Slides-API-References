---
title: ResourceLoading()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เมธอด callback ที่ควบคุมการโหลดทรัพยากรภายนอก.
type: docs
weight: 1
url: /th/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) เมธอด

เมธอด callback ที่ควบคุมการโหลดทรัพยากรภายนอก.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | ข้อมูลการโหลดทรัพยากร [IResourceLoadingArgs](../../iresourceloadingargs/). |

### ค่าที่ส่งคืน

การตัดสินใจโหลดทรัพยากร [ResourceLoadingAction](../../resourceloadingaction/).

## ดูเพิ่มเติม

* ประเภทนับ [ResourceLoadingAction](../../resourceloadingaction/)
* กำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IResourceLoadingArgs](../../iresourceloadingargs/)
* คลาส [IResourceLoadingCallback](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)