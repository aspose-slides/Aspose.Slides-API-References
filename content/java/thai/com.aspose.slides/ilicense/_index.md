---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /th/com.aspose.slides/ilicense/
---```
public interface ILicense
```

ให้เมธอดเพื่อให้ใบอนุญาตกับคอมโพเนนต์.

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
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | ให้ใบอนุญาตกับคอมโพเนนต์ |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | ให้ใบอนุญาตกับคอมโพเนนต์ |
| [resetLicense()](#resetLicense--) | รีเซ็ตใบอนุญาต |
| [isLicensed()](#isLicensed--) | ตรวจสอบว่ามีการใช้ใบอนุญาตกับคอมโพเนนต์หรือไม่ |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

ให้ใบอนุญาตกับคอมโพเนนต์.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| licenseName | java.lang.String | สามารถเป็นชื่อไฟล์เต็มหรือสั้นหรือชื่อของทรัพยากรที่ฝังอยู่ ใช้สตริงว่างเพื่อสลับเป็นโหมดประเมินผล |

--------------------

พยายามค้นหาใบอนุญาตในตำแหน่งต่อไปนี้:

1. เส้นทางที่ระบุโดยตรง.

2. โฟลเดอร์ของ component assembly.

3. โฟลเดอร์ของ assembly ที่เรียกของไคลเอนต์.

4. โฟลเดอร์ของ entry assembly.

5. ทรัพยากรฝังอยู่ใน assembly ที่เรียกของไคลเอนต์. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

ให้ใบอนุญาตกับคอมโพเนนต์.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีมที่มีใบอนุญาตอยู่ |

--------------------

ใช้เมธอดนี้เพื่อโหลดใบอนุญาตจากสตรีม. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

รีเซ็ตใบอนุญาต

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

ใช้เมธอดนี้เพื่อรีเซ็ตใบอนุญาตในคอมโพเนนต์

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

ตรวจสอบว่ามีการใช้ใบอนุญาตกับคอมโพเนนต์หรือไม่

**คืนค่า:**
boolean - true ถ้า component มีใบอนุญาต, false หากไม่