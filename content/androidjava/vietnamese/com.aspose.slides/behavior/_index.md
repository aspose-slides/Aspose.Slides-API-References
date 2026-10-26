---
title: Behavior
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn hành vi lớp cơ sở của hiệu ứng.
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
| [getAccumulate()](#getAccumulate--) | Biểu diễn việc các hành vi hoạt hình có được cộng dồn hay không. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Biểu diễn việc các hành vi hoạt hình có được cộng dồn hay không. |
| [getAdditive()](#getAdditive--) | Biểu diễn việc hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. |
| [setAdditive(int value)](#setAdditive-int-) | Biểu diễn việc hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. |
| [getProperties()](#getProperties--) | Biểu diễn các thuộc tính của hành vi. |
| [getTiming()](#getTiming--) | Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng. |
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


Biểu diễn việc các hành vi hoạt hình có được cộng dồn hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Biểu diễn việc các hành vi hoạt hình có được cộng dồn hay không. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Biểu diễn việc hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Trả về:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Biểu diễn việc hành vi hoạt hình hiện tại có được kết hợp với các hoạt hình đang chạy khác hay không. Đọc/ghi [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Biểu diễn các thuộc tính của hành vi. Chỉ đọc [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Trả về:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Trả về:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng. Đọc/ghi [ITiming](../../com.aspose.slides/itiming).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |