---
title: Metered
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: ให้เมธอดสำหรับตั้งค่ากุญแจเมตเดอร์.
type: docs
url: /th/com.aspose.slides/metered/
---
**Inheritance:**  
java.lang.Object  
```
public class Metered
```

Provides methods to set metered key.  
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) | สร้างอินสแตนซ์ใหม่ของคลาสนี้ |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | ตั้งค่า metered public และ private key |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | รับขนาดไฟล์การใช้ |
| [getConsumptionCredit()](#getConsumptionCredit--) | รับเครดิตการใช้ |
| [isMeteredLicensed()](#isMeteredLicensed--) | ตรวจสอบว่า metered ได้รับใบอนุญาตหรือไม่ |
### Metered() {#Metered--}
```
public Metered()
```

สร้างอินสแตนซ์ใหม่ของคลาสนี้

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

ตั้งค่า metered public และ private key. หากคุณซื้อใบอนุญาตแบบ metered, เมื่อเริ่มแอปพลิเคชัน, API นี้ควรถูกเรียก, โดยปกติแล้วนี่เพียงพอ. อย่างไรก็ตาม, หากการอัปโหลดข้อมูลการใช้ล้มเหลวตลอดและเกิน 24 ชั่วโมง, ใบอนุญาตจะถูกตั้งค่าเป็นสถานะประเมินผล, เพื่อหลีกเลี่ยงกรณีดังกล่าว, คุณควรตรวจสอบสถานะใบอนุญาตเป็นประจำ, หากเป็นสถานะประเมินผล, ให้เรียก API นี้อีกครั้ง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| publicKey | java.lang.String | public key |
| privateKey | java.lang.String | private key |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```

รับขนาดไฟล์การใช้

**คืนค่า:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```

รับเครดิตการใช้

**คืนค่า:**
double - จำนวนการใช้
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

ตรวจสอบว่า metered ได้รับใบอนุญาตหรือไม่

**คืนค่า:**
boolean - True or false