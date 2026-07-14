---
title: ILicense
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้เมธอดเพื่อกำหนดลิขสิทธิ์ให้กับคอมโพเนนต์.
type: docs
url: /th/com.aspose.slides/ilicense/
---```
public interface ILicense
```

ให้เมธอดเพื่อกำหนดลิขสิทธิ์ให้กับคอมโพเนนต์.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | กำหนดลิขสิทธิ์ให้กับคอมโพเนนต์ |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | กำหนดลิขสิทธิ์ให้กับคอมโพเนนต์ |
| [resetLicense()](#resetLicense--) | รีเซ็ตลิขสิทธิ์ |
| [isLicensed()](#isLicensed--) | ตรวจสอบว่าลิขสิทธิ์ถูกใช้กับคอมโพเนนต์หรือไม่ |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


กำหนดลิขสิทธิ์ให้กับคอมโพเนนต์.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| licenseName | java.lang.String | สามารถเป็นชื่อไฟล์เต็มหรือสั้น หรือชื่อของทรัพยากรที่ฝังอยู่ได้ ใช้สตริงว่างเพื่อสลับไปยังโหมดประเมินผล |

--------------------

พยายามค้นหาลิขสิทธิ์ในตำแหน่งต่อไปนี้:

1. เส้นทางที่ระบุโดยชัดเจน.

2. โฟลเดอร์ของการประกอบคอมโพเนนต์.

3. โฟลเดอร์ของการประกอบที่เรียกโดยไคลเอนต์.

4. โฟลเดอร์ของการประกอบเริ่มต้น.

5. ทรัพยากรที่ฝังอยู่ในการประกอบที่เรียกโดยไคลเอนต์. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


กำหนดลิขสิทธิ์ให้กับคอมโพเนนต์.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่มีลิขสิทธิ์อยู่ |

--------------------

ใช้เมธอดนี้เพื่อโหลดลิขสิทธิ์จากสตรีม. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


รีเซ็ตลิขสิทธิ์

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

ใช้เมธอดนี้เพื่อรีเซ็ตลิขสิทธิ์ในคอมโพเนนต์

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


ตรวจสอบว่าลิขสิทธิ์ถูกใช้กับคอมโพเนนต์หรือไม่

**คืนค่า:**
boolean - true หากคอมโพเนนต์มีลิขสิทธิ์, false หากไม่มี