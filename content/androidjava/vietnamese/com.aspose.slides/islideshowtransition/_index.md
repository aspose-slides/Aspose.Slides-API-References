---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho chuyển đổi trình chiếu.
type: docs
url: /vi/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Đại diện cho chuyển đổi trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSound()](#getSound--) | Trả về hoặc đặt dữ liệu âm thanh nhúng. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Trả về hoặc đặt dữ liệu âm thanh nhúng. |
| [getSoundMode()](#getSoundMode--) | Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. |
| [getSoundLoop()](#getSoundLoop--) | Thuộc tính này chỉ định liệu âm thanh sẽ lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Thuộc tính này chỉ định liệu âm thanh sẽ lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Xác định việc một cú nhấp chuột sẽ tiến đến slide tiếp theo hay không. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Xác định việc một cú nhấp chuột sẽ tiến đến slide tiếp theo hay không. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Thuộc tính này chỉ định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một thời gian nhất định. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Thuộc tính này chỉ định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một thời gian nhất định. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. |
| [getSpeed()](#getSpeed--) | Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. |
| [setSpeed(int value)](#setSpeed-int-) | Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. |
| [getValue()](#getValue--) | Giá trị chuyển đổi trình chiếu. |
| [getType()](#getType--) | Kiểu chuyển đổi. |
| [setType(int value)](#setType-int-) | Kiểu chuyển đổi. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. |
| [getSoundName()](#getSoundName--) | Xác định tên đọc được cho âm thanh của chuyển đổi. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Xác định tên đọc được cho âm thanh của chuyển đổi. |
| [getDuration()](#getDuration--) | Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. |
| [setDuration(int value)](#setDuration-int-) | Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Trả về hoặc đặt dữ liệu âm thanh nhúng. Đọc-ghi [IAudio](../../com.aspose.slides/iaudio).

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Trả về hoặc đặt dữ liệu âm thanh nhúng. Đọc-ghi [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. Đọc-ghi [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Trả về:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. Đọc-ghi [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Thuộc tính này chỉ định liệu âm thanh sẽ lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu. Đọc-ghi boolean.

**Trả về:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Thuộc tính này chỉ định liệu âm thanh sẽ lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu. Đọc-ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Xác định việc một cú nhấp chuột sẽ tiến đến slide tiếp theo hay không. Nếu thuộc tính này không được chỉ định thì giá trị true được giả định. Đọc-ghi boolean.

**Trả về:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Xác định việc một cú nhấp chuột sẽ tiến đến slide tiếp theo hay không. Nếu thuộc tính này không được chỉ định thì giá trị true được giả định. Đọc-ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Thuộc tính này chỉ định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một thời gian nhất định. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Lấy chuyển đổi slide đầu tiên
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kiểm tra xem cờ Advance Slide After có được bật không
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Lấy giá trị thời gian Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Thuộc tính này chỉ định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một thời gian nhất định. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Lấy chuyển đổi slide đầu tiên
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Kiểm tra xem cờ Advance Slide After có được bật không
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Lấy giá trị thời gian Advance Slide After
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. Cài đặt này có thể được dùng cùng với thuộc tính advClick. Nếu thuộc tính này không được chỉ định thì giả định không có tự động chuyển tiếp. Đọc-ghi long.

**Trả về:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. Cài đặt này có thể được dùng cùng với thuộc tính advClick. Nếu thuộc tính này không được chỉ định thì giả định không có tự động chuyển tiếp. Đọc-ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. Đọc-ghi [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Trả về:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. Đọc-ghi [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Giá trị chuyển đổi trình chiếu. Chỉ-đọc [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Trả về:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Kiểu chuyển đổi. Đọc-ghi [TransitionType](../../com.aspose.slides/transitiontype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Kiểu chuyển đổi. Đọc-ghi [TransitionType](../../com.aspose.slides/transitiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. Nếu thuộc tính này được đặt thành true thì ứng dụng tạo ra sẽ được thông báo kiểm tra thuộc tính name được chỉ định cho âm thanh này trong danh sách âm thanh tích hợp sẵn và có thể hiển thị tên tùy chỉnh hoặc giao diện người dùng phù hợp. Đọc-ghi boolean.

**Trả về:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. Nếu thuộc tính này được đặt thành true thì ứng dụng tạo ra sẽ được thông báo kiểm tra thuộc tính name được chỉ định cho âm thanh này trong danh sách âm thanh tích hợp sẵn và có thể hiển thị tên tùy chỉnh hoặc giao diện người dùng phù hợp. Đọc-ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Xác định tên đọc được cho âm thanh của chuyển đổi. Thuộc tính (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) phải được gán để lấy hoặc đặt tên âm thanh. Đọc-ghi String.

**Trả về:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Xác định tên đọc được cho âm thanh của chuyển đổi. Thuộc tính \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) phải được gán để lấy hoặc đặt tên âm thanh. Đọc-ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. Đọc/ghi int.

--------------------

Tương ứng với thuộc tính p14:dur của phần tử p:transition trong schema PresentationML. Nếu không được đặt, thời lượng sẽ được xác định tự động dựa trên thuộc tính \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) và kiểu chuyển đổi.

**Trả về:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. Đọc/ghi int.

--------------------

Tương ứng với thuộc tính p14:dur của phần tử p:transition trong schema PresentationML. Nếu không được đặt, thời lượng sẽ được xác định tự động dựa trên thuộc tính \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) và kiểu chuyển đổi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |