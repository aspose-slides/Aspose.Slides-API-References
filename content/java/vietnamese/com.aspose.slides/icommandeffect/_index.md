---
title: ICommandEffect
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một hiệu ứng lệnh cho hành vi hoạt hình.
type: docs
url: /vi/com.aspose.slides/icommandeffect/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Biểu diễn một hiệu ứng lệnh cho hành vi hoạt hình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Defines command effect type of behavior. |
| [setType(byte value)](#setType-byte-) | Defines command effect type of behavior. |
| [getCommandString()](#getCommandString--) | Defines command string. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Defines command string. |
| [getShapeTarget()](#getShapeTarget--) | Defines shape target of command effect. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Defines shape target of command effect. |
### getType() {#getType--}
```
public abstract byte getType()
```

Xác định loại hiệu ứng lệnh của hành vi. Đọc/ghi [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Trả về:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Xác định loại hiệu ứng lệnh của hành vi. Đọc/ghi [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Xác định chuỗi lệnh. Đọc/ghi String.

**Trả về:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Xác định chuỗi lệnh. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Xác định mục tiêu hình dạng của hiệu ứng lệnh. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Trả về:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Xác định mục tiêu hình dạng của hiệu ứng lệnh. Đọc/ghi [IShape](../../com.aspose.slides/ishape).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |