---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /th/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติของโครงสร้างแบบอักษรที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getMinor()](#getMinor--) | ส่งคืนคอลเลกชันของแบบอักษรสำหรับส่วน "body" ของสไลด์ |
| [getMajor()](#getMajor--) | ส่งคืนคอลเลกชันของแบบอักษรสำหรับส่วน "heading" ของสไลด์ |
| [getName()](#getName--) | ส่งคืนชื่อของโครงสร้างแบบอักษร |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


ส่งคืนคอลเลกชันของแบบอักษรสำหรับส่วน "body" ของสไลด์ อ่านอย่างเดียว [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**คืนค่า:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


ส่งคืนคอลเลกชันของแบบอักษรสำหรับส่วน "heading" ของสไลด์ อ่านอย่างเดียว [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**คืนค่า:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


ส่งคืนชื่อของโครงสร้างแบบอักษร อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String