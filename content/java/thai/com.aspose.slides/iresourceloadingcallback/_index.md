---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: อินเทอร์เฟซการเรียกกลับที่ใช้จัดการการโหลดทรัพยากรภายนอก
type: docs
url: /th/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

อินเทอร์เฟซการเรียกกลับที่ใช้จัดการการโหลดทรัพยากรภายนอก
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | เมธอดการเรียกกลับที่ควบคุมการโหลดทรัพยากรภายนอก |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


เมธอดการเรียกกลับที่ควบคุมการโหลดทรัพยากรภายนอก

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | ข้อมูลทรัพยากรที่กำลังโหลด [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**ผลลัพธ์:**
int - การตัดสินใจการโหลดทรัพยากร [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).