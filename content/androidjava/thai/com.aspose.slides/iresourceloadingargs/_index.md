---
title: IResourceLoadingArgs
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อินเทอร์เฟซสำหรับอาร์กิวเมนต์การโหลดทรัพยากรภายนอก.
type: docs
url: /th/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

อินเทอร์เฟซสำหรับอาร์กิวเมนต์การโหลดทรัพยากรภายนอก.
## วิธีการ

| Method | Description |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI ดั้งเดิมของทรัพยากรตามที่ระบุในงานนำเสนอที่นำเข้า. |
| [getUri()](#getUri--) | URI ของทรัพยากรที่ใช้สำหรับการดาวน์โหลดถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI ของทรัพยากรที่ใช้สำหรับการดาวน์โหลดถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | ตั้งค่าข้อมูลที่ผู้ใช้ให้ของทรัพยากรที่จะใช้ถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI ดั้งเดิมของทรัพยากรตามที่ระบุในงานนำเสนอที่นำเข้า.

**คืนค่า:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI ของทรัพยากรที่ใช้สำหรับการดาวน์โหลดถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). โดยเริ่มแรกจะถูกตั้งค่าเป็น URI ดั้งเดิมของทรัพยากร แต่สามารถกำหนดค่าใหม่เป็นค่าใดก็ได้.

**คืนค่า:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI ของทรัพยากรที่ใช้สำหรับการดาวน์โหลดถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). โดยเริ่มแรกจะถูกตั้งค่าเป็น URI ดั้งเดิมของทรัพยากร แต่สามารถกำหนดค่าใหม่เป็นค่าใดก็ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


ตั้งค่าข้อมูลที่ผู้ใช้ให้ของทรัพยากรที่จะใช้ถ้า [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) คืนค่า [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูลที่ให้ของทรัพยากร byte[] |