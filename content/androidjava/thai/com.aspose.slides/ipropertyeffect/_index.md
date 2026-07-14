---
title: IPropertyEffect
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงพฤติกรรมของเอฟเฟ็กต์คุณสมบัติ
type: docs
url: /th/com.aspose.slides/ipropertyeffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

แสดงพฤติกรรมของเอฟเฟ็กต์คุณสมบัติ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ระบุค่าตั้งต้นของการเคลื่อนไหว. |
| [setFrom(String value)](#setFrom-java.lang.String-) | ระบุค่าตั้งต้นของการเคลื่อนไหว. |
| [getTo()](#getTo--) | ระบุค่าที่สิ้นสุดของการเคลื่อนไหว. |
| [setTo(String value)](#setTo-java.lang.String-) | ระบุค่าที่สิ้นสุดของการเคลื่อนไหว. |
| [getBy()](#getBy--) | ระบุค่าการออฟเซตเชิงสัมพัทธ์ของการเคลื่อนไหวโดยสัมพันธ์กับตำแหน่งก่อนเริ่มการเคลื่อนไหว. |
| [setBy(String value)](#setBy-java.lang.String-) | ระบุค่าการออฟเซตเชิงสัมพัทธ์ของการเคลื่อนไหวโดยสัมพันธ์กับตำแหน่งก่อนเริ่มการเคลื่อนไหว. |
| [getValueType()](#getValueType--) | ระบุประเภทของค่าคุณสมบัติ. |
| [setValueType(int value)](#setValueType-int-) | ระบุประเภทของค่าคุณสมบัติ. |
| [getCalcMode()](#getCalcMode--) | ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | ระบุจุดของการเคลื่อนไหว. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | ระบุจุดของการเคลื่อนไหว. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

ระบุค่าตั้งต้นของการเคลื่อนไหว. Read/write String.

**คืนค่า:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

ระบุค่าตั้งต้นของการเคลื่อนไหว. Read/write String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

ระบุค่าที่สิ้นสุดของการเคลื่อนไหว. Read/write String.

**คืนค่า:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

ระบุค่าที่สิ้นสุดของการเคลื่อนไหว. Read/write String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

ระบุค่าการออฟเซตเชิงสัมพัทธ์ของการเคลื่อนไหวโดยสัมพันธ์กับตำแหน่งก่อนเริ่มการเคลื่อนไหว. Read/write String.

**คืนค่า:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

ระบุค่าการออฟเซตเชิงสัมพัทธ์ของการเคลื่อนไหวโดยสัมพันธ์กับตำแหน่งก่อนเริ่มการเคลื่อนไหว. Read/write String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

ระบุประเภทของค่าคุณสมบัติ. Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**คืนค่า:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

ระบุประเภทของค่าคุณสมบัติ. Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**คืนค่า:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

ระบุโหมดการแทรกค่ากลางสำหรับการเคลื่อนไหว Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

ระบุจุดของการเคลื่อนไหว. Read/write [IPointCollection](../../com.aspose.slides/ipointcollection).

**คืนค่า:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

ระบุจุดของการเคลื่อนไหว. Read/write [IPointCollection](../../com.aspose.slides/ipointcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |