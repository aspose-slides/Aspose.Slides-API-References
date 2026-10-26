---
title: IRotation3D
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: نمایانگر چرخش سه‌بعدی یک نمودار.
type: docs
url: /fa/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

نمایانگر چرخش سه‌بعدی یک نمودار.
## متدها

| متد | توضیح |
| --- | --- |
| [getRotationX()](#getRotationX--) | مقدار یا تنظیم درجه چرخش حول محور X، یعنی |
| [setRotationX(byte value)](#setRotationX-byte-) | مقدار یا تنظیم درجه چرخش حول محور X، یعنی |
| [getRotationY()](#getRotationY--) | مقدار یا تنظیم درجه چرخش حول محور Y، یعنی |
| [setRotationY(int value)](#setRotationY-int-) | مقدار یا تنظیم درجه چرخش حول محور Y، یعنی |
| [getPerspective()](#getPerspective--) | مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D (بین 0 تا 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D (بین 0 تا 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | تعیین می‌کند که محورها در زاویه راست باشند نه به صورت پرسپکتیو کشیده شوند. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | تعیین می‌کند که محورها در زاویه راست باشند نه به صورت پرسپکتیو کشیده شوند. |
| [getDepthPercents()](#getDepthPercents--) | مقدار یا تنظیم عمق نمودار 3D به صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | مقدار یا تنظیم عمق نمودار 3D به صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). |
| [getHeightPercents()](#getHeightPercents--) | تعیین ارتفاع نمودار 3-D به صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | تعیین ارتفاع نمودار 3-D به صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی در جهت Y برای نمودارهای 3D (بین -90 و 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن byte.

**بازگشت:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی در جهت Y برای نمودارهای 3D (بین -90 و 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی در جهت X برای نمودارهای 3D (بین 0 و 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن int.

**بازگشت:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی در جهت X برای نمودارهای 3D (بین 0 و 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D (بین 0 تا 100). اگر مقدار ویژگی RightAngleAxes true باشد نادیده گرفته می‌شود. قابل خواندن/نوشتن byte.

**بازگشت:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D (بین 0 تا 100). اگر مقدار ویژگی RightAngleAxes true باشد نادیده گرفته می‌شود. قابل خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

تعیین می‌کند که محورها در زاویه راست باشند نه به صورت پرسپکتیو کشیده شوند. به عبارت دیگر تعیین می‌کند که زوایای محورها مستقل از چرخش یا ارتفاع نمودار باشند. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

تعیین می‌کند که محورها در زاویه راست باشند نه به صورت پرسپکتیو کشیده شوند. به عبارت دیگر تعیین می‌کند که زوایای محورها مستقل از چرخش یا ارتفاع نمودار باشند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

مقدار یا تنظیم عمق نمودار 3D به صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). قابل خواندن/نوشتن int.

**بازگشت:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

مقدار یا تنظیم عمق نمودار 3D به صورت درصدی از عرض نمودار (بین 20 تا 2000 درصد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

تعیین ارتفاع نمودار 3-D به صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). قابل خواندن/نوشتن int.

**بازگشت:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

تعیین ارتفاع نمودار 3-D به صورت درصدی از عرض نمودار (بین 5 تا 500 درصد). قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |