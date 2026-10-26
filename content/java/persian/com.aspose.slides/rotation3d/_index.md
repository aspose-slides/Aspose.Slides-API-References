---
title: Rotation3D
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش چرخش سه‌بعدی یک نمودار.
type: docs
url: /fa/com.aspose.slides/rotation3d/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

نمایش چرخش سه‌بعدی یک نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getRotationX()](#getRotationX--) | مقدار یا تنظیم درجه چرخش حول محور X، به عبارت دیگر |
| [setRotationX(byte value)](#setRotationX-byte-) | مقدار یا تنظیم درجه چرخش حول محور X، به عبارت دیگر |
| [getRotationY()](#getRotationY--) | مقدار یا تنظیم درجه چرخش حول محور Y، به عبارت دیگر |
| [setRotationY(int value)](#setRotationY-int-) | مقدار یا تنظیم درجه چرخش حول محور Y، به عبارت دیگر |
| [getPerspective()](#getPerspective--) | مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 و 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 و 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | تعیین می‌کند آیا محورهای نمودار در زاویه‌های راست قرار دارند یا به‌صورت پرسپکتیو رسم می‌شوند. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | تعیین می‌کند آیا محورهای نمودار در زاویه‌های راست قرار دارند یا به‌صورت پرسپکتیو رسم می‌شوند. |
| [getDepthPercents()](#getDepthPercents--) | مقدار یا تنظیم عمق یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | مقدار یا تنظیم عمق یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). |
| [getHeightPercents()](#getHeightPercents--) | تعیین ارتفاع یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | تعیین ارتفاع یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی در جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و با گزینه «Y Rotation» در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی بایت.

**بازگشت:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی در جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و با گزینه «Y Rotation» در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی بایت.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی در جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و با گزینه «X Rotation» در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی int.

**بازگشت:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی در جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.158 rotY (Y Rotation) در ECMA-376 و با گزینه «X Rotation» در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 و 240). اگر ویژگی RightAngleAxes مقدار true داشته باشد، نادیده گرفته می‌شود. خواندنی/نوشتنی بایت.

**بازگشت:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 و 240). اگر ویژگی RightAngleAxes مقدار true داشته باشد، نادیده گرفته می‌شود. خواندنی/نوشتنی بایت.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

تعیین می‌کند آیا محورهای نمودار در زاویه‌های راست قرار دارند یا به‌صورت پرسپکتیو رسم می‌شوند. به عبارت دیگر، تعیین می‌کند آیا زاویه‌های محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

تعیین می‌کند آیا محورهای نمودار در زاویه‌های راست قرار دارند یا به‌صورت پرسپکتیو رسم می‌شوند. به عبارت دیگر، تعیین می‌کند آیا زاویه‌های محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

مقدار یا تنظیم عمق یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). خواندنی/نوشتنی int.

**بازگشت:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

مقدار یا تنظیم عمق یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

تعیین ارتفاع یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). خواندنی/نوشتنی int.

**بازگشت:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

تعیین ارتفاع یک نمودار سه‌بعدی به‌صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

بازگرداندن شیء Parent_Immediate. فقط-قابل-خواندن IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject