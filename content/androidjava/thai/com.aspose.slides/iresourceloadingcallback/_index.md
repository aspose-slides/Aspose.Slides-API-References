---
title: IResourceLoadingCallback
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อินเทอร์เฟซ Callback ที่ใช้จัดการการโหลดทรัพยากรภายนอก
type: docs
url: /th/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

อินเทอร์เฟซ Callback ที่ใช้จัดการการโหลดทรัพยากรภายนอก
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | วิธี Callback ที่กำหนดการโหลดทรัพยากรภายนอก |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

วิธี Callback ที่กำหนดการโหลดทรัพยากรภายนอก

**Parameters:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | ข้อมูลการโหลดทรัพยากร [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Returns:**
int - การตัดสินใจการโหลดทรัพยากร [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).