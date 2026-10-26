---
title: Behavior
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị hành vi lớp cơ sở của hiệu ứng.
type: docs
url: /vi/com.aspose.slides/behavior/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Biểu diễn hành vi lớp cơ sở của hiệu ứng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Biểu thị liệu các hành vi hoạt ảnh có được tích lũy hay không. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Biểu thị liệu các hành vi hoạt ảnh có được tích lũy hay không. |
| [getAdditive()](#getAdditive--) | Biểu thị liệu hành vi hoạt ảnh hiện tại có được kết hợp với các hoạt ảnh đang chạy khác hay không. |
| [setAdditive(int value)](#setAdditive-int-) | Biểu thị liệu hành vi hoạt ảnh hiện tại có được kết hợp với các hoạt ảnh đang chạy khác hay không. |
| [getProperties()](#getProperties--) | Biểu thị các thuộc tính của hành vi. |
| [getTiming()](#getTiming--) | Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Biểu thị liệu các hành vi hoạt ảnh có được tích lũy hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Biểu thị liệu các hành vi hoạt ảnh có được tích lũy hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Biểu thị liệu hành vi hoạt ảnh hiện tại có được kết hợp với các hoạt ảnh đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Trả về:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Biểu thị liệu hành vi hoạt ảnh hiện tại có được kết hợp với các hoạt ảnh đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Biểu thị các thuộc tính của hành vi. Chỉ đọc [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Trả về:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Trả về:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |