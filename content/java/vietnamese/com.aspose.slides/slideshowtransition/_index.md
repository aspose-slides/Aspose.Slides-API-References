---
title: SlideShowTransition
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho chuyển đổi trình chiếu.
type: docs
url: /vi/com.aspose.slides/slideshowtransition/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Đại diện cho chuyển đổi trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSound()](#getSound--) | Trả về hoặc đặt dữ liệu âm thanh nhúng. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Trả về hoặc đặt dữ liệu âm thanh nhúng. |
| [getSoundMode()](#getSoundMode--) | Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. |
| [getSoundLoop()](#getSoundLoop--) | Thuộc tính này xác định liệu âm thanh có lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu hay không. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Thuộc tính này xác định liệu âm thanh có lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu hay không. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Xác định liệu một cú nhấp chuột chuột có tiến tới slide tiếp theo hay không. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Xác định liệu một cú nhấp chuột chuột có tiến tới slide tiếp theo hay không. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Thuộc tính này xác định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một khoảng thời gian nhất định. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Thuộc tính này xác định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một khoảng thời gian nhất định. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. |
| [getSpeed()](#getSpeed--) | Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. |
| [setSpeed(int value)](#setSpeed-int-) | Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. |
| [getValue()](#getValue--) | Giá trị chuyển đổi trình chiếu. |
| [getType()](#getType--) | Loại chuyển đổi. |
| [setType(int value)](#setType-int-) | Loại chuyển đổi. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. |
| [getSoundName()](#getSoundName--) | Xác định tên đọc được cho âm thanh của chuyển đổi. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Xác định tên đọc được cho âm thanh của chuyển đổi. |
| [getDuration()](#getDuration--) | Lấy hoặc đặt thời lượng hiệu ứng chuyển đổi slide tính bằng mili giây. |
| [setDuration(int value)](#setDuration-int-) | Lấy hoặc đặt thời lượng hiệu ứng chuyển đổi slide tính bằng mili giây. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định liệu hai đối tượng SlideShowTransition có bằng nhau hay không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể, phù hợp cho các thuật toán băm và cấu trúc dữ liệu như bảng băm. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Trả về hoặc đặt dữ liệu âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Trả về hoặc đặt dữ liệu âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. Đọc/ghi [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Trả về:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Đặt hoặc trả về chế độ âm thanh cho chuyển đổi slide. Đọc/ghi [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Thuộc tính này xác định liệu âm thanh có lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Thuộc tính này xác định liệu âm thanh có lặp lại cho đến khi sự kiện âm thanh tiếp theo xảy ra trong trình chiếu hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Xác định liệu một cú nhấp chuột chuột có tiến tới slide tiếp theo hay không. Nếu thuộc tính này không được chỉ định, sẽ giả sử giá trị true. Đọc/ghi boolean.

**Trả về:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Xác định liệu một cú nhấp chuột chuột có tiến tới slide tiếp theo hay không. Nếu thuộc tính này không được chỉ định, sẽ giả sử giá trị true. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Thuộc tính này xác định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một khoảng thời gian nhất định. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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
public final void setAdvanceAfter(boolean value)
```

Thuộc tính này xác định liệu trình chiếu sẽ chuyển sang slide tiếp theo sau một khoảng thời gian nhất định. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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
public final long getAdvanceAfterTime()
```

Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. Cài đặt này có thể được sử dụng cùng với thuộc tính advClick. Nếu thuộc tính này không được chỉ định, sẽ giả sử không có tự động tiến tới. Đọc/ghi long.

**Trả về:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Xác định thời gian, tính bằng mili giây, sau đó chuyển đổi sẽ bắt đầu. Cài đặt này có thể được sử dụng cùng với thuộc tính advClick. Nếu thuộc tính này không được chỉ định, sẽ giả sử không có tự động tiến tới. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. Đọc/ghi [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Trả về:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Xác định tốc độ chuyển đổi sẽ được sử dụng khi chuyển từ slide hiện tại sang slide tiếp theo. Đọc/ghi [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Giá trị chuyển đổi trình chiếu. Chỉ đọc [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Trả về:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Loại chuyển đổi. Đọc/ghi [TransitionType](../../com.aspose.slides/transitiontype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Loại chuyển đổi. Đọc/ghi [TransitionType](../../com.aspose.slides/transitiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. Nếu thuộc tính này được đặt thành true, ứng dụng tạo ra sẽ được thông báo để kiểm tra thuộc tính name được chỉ định cho âm thanh này trong danh sách âm thanh tích hợp sẵn và có thể hiển thị tên tùy chỉnh hoặc giao diện người dùng cần thiết. Đọc/Ghi boolean.

**Trả về:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Xác định liệu âm thanh này có phải là âm thanh tích hợp sẵn hay không. Nếu thuộc tính này được đặt thành true, ứng dụng tạo ra sẽ được thông báo để kiểm tra thuộc tính name được chỉ định cho âm thanh này trong danh sách âm thanh tích hợp sẵn và có thể hiển thị tên tùy chỉnh hoặc giao diện người dùng cần thiết. Đọc/Ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Xác định tên đọc được cho âm thanh của chuyển đổi. Thuộc tính Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) phải được gán để lấy hoặc đặt tên âm thanh. Đọc/Ghi String.

**Trả về:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Xác định tên đọc được cho âm thanh của chuyển đổi. Thuộc tính Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) phải được gán để lấy hoặc đặt tên âm thanh. Đọc/Ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. Đọc/ghi int.

--------------------

Tương ứng với thuộc tính p14:dur của phần tử p:transition trong schema PresentationML. Nếu không được đặt, thời lượng sẽ được xác định tự động dựa trên thuộc tính \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) và loại chuyển đổi.

**Trả về:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Lấy hoặc đặt thời lượng của hiệu ứng chuyển đổi slide tính bằng mili giây. Đọc/ghi int.

--------------------

Tương ứng với thuộc tính p14:dur của phần tử p:transition trong schema PresentationML. Nếu không được đặt, thời lượng sẽ được xác định tự động dựa trên thuộc tính \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) và loại chuyển đổi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định liệu hai đối tượng SlideShowTransition có bằng nhau hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition để so sánh với SlideShowTransition hiện tại. |

**Trả về:**
boolean - **true** nếu SlideShowTransition được chỉ định bằng với SlideShowTransition hiện tại; ngược lại, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể, phù hợp cho các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int - 23454

--------------------

Được ghi đè để làm cho trình biên dịch hài lòng. Luôn trả về hằng số vì đối tượng có thể thay đổi.