---
title: Metered
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้เมธอดสำหรับตั้งค่ากุญแจ metered.
type: docs
url: /th/com.aspose.slides/metered/
---
**การสืบทอด:**
java.lang.Object
```
public class Metered
```

ให้เมธอดสำหรับตั้งค่ากุญแจ metered.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Metered()](#Metered--) | สร้างอินสแตนซ์ใหม่ของคลาสนี้. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | ตั้งค่า metered public และ private key. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | รับขนาดไฟล์การใช้ |
| [getConsumptionCredit()](#getConsumptionCredit--) | รับเครดิตการใช้ |
| [isMeteredLicensed()](#isMeteredLicensed--) | ตรวจสอบว่า metered มีใบอนุญาตหรือไม่ |
### Metered() {#Metered--}
```
public Metered()
```

สร้างอินสแตนซ์ใหม่ของคลาสนี้.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```

ตั้งค่า metered public และ private key. หากคุณซื้อใบอนุญาตแบบ metered เมื่อเริ่มแอปพลิเคชัน ควรเรียก API นี้ ปกติแล้วเพียงเรียกครั้งเดียวก็เพียงพอ อย่างไรก็ตาม หากการอัปโหลดข้อมูลการใช้ล้มเหลวอย่างต่อเนื่องและเกิน 24 ชั่วโมง ใบอนุญาตจะถูกตั้งเป็นสถานะการประเมินผล เพื่อหลีกเลี่ยงกรณีดังกล่าว คุณควรตรวจสอบสถานะใบอนุญาตเป็นประจำ หากอยู่ในสถานะการประเมินผล ให้เรียก API นี้อีกครั้ง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| publicKey | java.lang.String | คีย์สาธารณะ |
| privateKey | java.lang.String | คีย์ส่วนตัว |

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
double - ปริมาณการใช้
### isMeteredLicensed() {#isMeteredLicensed--}
```
public static boolean isMeteredLicensed()
```

ตรวจสอบว่า metered มีใบอนุญาตหรือไม่

**คืนค่า:**
boolean - จริงหรือเท็จ