---
title: Rotation3D
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر چرخش سه‌بعدی یک نمودار.
type: docs
url: /fa/com.aspose.slides/rotation3d/
---
**وراثت:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

چرخش سه‌بعدی یک نمودار را نمایش می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getRotationX()](#getRotationX--) | مقدار درجهٔ چرخش حول محور X را بر می‌گرداند یا تنظیم می‌کند، یعنی |
| [setRotationX(byte value)](#setRotationX-byte-) | مقدار درجهٔ چرخش حول محور X را بر می‌گرداند یا تنظیم می‌کند، یعنی |
| [getRotationY()](#getRotationY--) | مقدار درجهٔ چرخش حول محور Y را بر می‌گرداند یا تنظیم می‌کند، یعنی |
| [setRotationY(int value)](#setRotationY-int-) | مقدار درجهٔ چرخش حول محور Y را بر می‌گرداند یا تنظیم می‌کند، یعنی |
| [getPerspective()](#getPerspective--) | مقدار پرسپکتیو (زاویهٔ میدان دید) را برای نمودارهای سه‌بعدی تنظیم یا بر می‌گرداند (بین 0 و 240). |
| [setPerspective(byte value)](#setPerspective-byte-) | مقدار پرسپکتیو (زاویهٔ میدان دید) را برای نمودارهای سه‌بعدی تنظیم یا بر می‌گرداند (بین 0 و 240). |
| [getRightAngleAxes()](#getRightAngleAxes--) | تعیین می‌کند که محورها به‌صورت زاویهٔ راست باشند یا به‌جایش در پرسپکتیو ترسیم شوند. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | تعیین می‌کند که محورها به‌صورت زاویهٔ راست باشند یا به‌جایش در پرسپکتیو ترسیم شوند. |
| [getDepthPercents()](#getDepthPercents--) | عمق یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم یا بر می‌گرداند (بین 20 تا 2000 درصد). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | عمق یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم یا بر می‌گرداند (بین 20 تا 2000 درصد). |
| [getHeightPercents()](#getHeightPercents--) | ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 5 تا 500 درصد). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 5 تا 500 درصد). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

مقدار درجهٔ چرخش حول محور X را بر می‌گرداند یا تنظیم می‌کند، یعنی در جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و با گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن بایت.

**بازمی‌گرداند:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

مقدار درجهٔ چرخش حول محور X را بر می‌گرداند یا تنظیم می‌کند، یعنی در جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و با گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن بایت.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

مقدار درجهٔ چرخش حول محور Y را بر می‌گرداند یا تنظیم می‌کند، یعنی در جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و با گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن int.

**بازمی‌گرداند:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

مقدار درجهٔ چرخش حول محور Y را بر می‌گرداند یا تنظیم می‌کند، یعنی در جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و با گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

مقدار پرسپکتیو (زاویهٔ میدان دید) را برای نمودارهای سه‌بعدی تنظیم یا بر می‌گرداند (بین 0 تا 240). اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. قابل خواندن/نوشتن بایت.

**بازمی‌گرداند:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

مقدار پرسپکتیو (زاویهٔ میدان دید) را برای نمودارهای سه‌بعدی تنظیم یا بر می‌گرداند (بین 0 تا 240). اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. قابل خواندن/نوشتن بایت.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

تعیین می‌کند که محورها به‌صورت زاویهٔ راست باشند یا به‌جایش در پرسپکتیو ترسیم شوند. به عبارت دیگر، تعیین می‌کند که زوایای محورها مستقل از چرخش یا ارتفاع نمودار باشند. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

تعیین می‌کند که محورها به‌صورت زاویهٔ راست باشند یا به‌جایش در پرسپکتیو ترسیم شوند. به عبارت دیگر، تعیین می‌کند که زوایای محورها مستقل از چرخش یا ارتفاع نمودار باشند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

عمق یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم یا بر می‌گرداند (بین 20 تا 2000 درصد). قابل خواندن/نوشتن int.

**بازمی‌گرداند:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

عمق یک نمودار سه‌بعاد را به‌عنوان درصدی از عرض نمودار تنظیم یا بر می‌گرداند (بین 20 تا 2000 درصد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 5 تا 500 درصد). قابل خواندن/نوشتن int.

**بازمی‌گرداند:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 5 تا 500 درصد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بر می‌گرداند. فقط-خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject