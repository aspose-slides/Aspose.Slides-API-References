---
title: IBehavior
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu thị hành vi lớp cơ sở của hiệu ứng.
type: docs
url: /vi/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Biểu thị hành vi lớp cơ sở của hiệu ứng.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Biểu thị liệu các hành vi hoạt hình có được tích lũy hay không. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Biểu thị liệu các hành vi hoạt hình có được tích lũy hay không. |
| [getAdditive()](#getAdditive--) | Biểu thị liệu hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. |
| [setAdditive(int value)](#setAdditive-int-) | Biểu thị liệu hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. |
| [getProperties()](#getProperties--) | Biểu thị các thuộc tính của hành vi. |
| [getTiming()](#getTiming--) | Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Biểu thị liệu các hành vi hoạt hình có được tích lũy hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Biểu thị liệu các hành vi hoạt hình có được tích lũy hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Biểu thị liệu hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Trả về:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Biểu thị liệu hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Biểu thị các thuộc tính của hành vi. Chỉ đọc [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Trả về:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Trả về:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |