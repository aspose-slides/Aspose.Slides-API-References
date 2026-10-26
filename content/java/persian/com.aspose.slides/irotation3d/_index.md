---
title: IRotation3D
second_title: Aspose.Slides for Java API Reference
description: نماینده چرخش سه‌بعدی یک نمودار.
type: docs
url: /fa/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

نمایش چرخش سه‌بعدی یک نمودار.
## متدها

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | Returns or sets the rotation degree around the X-axis, i.e. |
| [setRotationX(byte value)](#setRotationX-byte-) | Returns or sets the rotation degree around the X-axis, i.e. |
| [getRotationY()](#getRotationY--) | Returns or sets the rotation degree around the Y-axis, i.e. |
| [setRotationY(int value)](#setRotationY-int-) | Returns or sets the rotation degree around the Y-axis, i.e. |
| [getPerspective()](#getPerspective--) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). |
| [setPerspective(byte value)](#setPerspective-byte-) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Determines whether the chart axes are at right angles, rather than drawn in perspective. |
| [getDepthPercents()](#getDepthPercents--) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent). |
| [getHeightPercents()](#getHeightPercents--) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی بایت.

**بازگشت:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

مقدار یا تنظیم درجه چرخش حول محور X، یعنی جهت Y برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه). این ویژگی با مورد 21.2.157 rotX (X Rotation) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی بایت.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی int.

**بازگشت:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

مقدار یا تنظیم درجه چرخش حول محور Y، یعنی جهت X برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه). این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی/نوشتنی int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 تا 100). در صورت true بودن مقدار ویژگی RightAngleAxes نادیده گرفته می‌شود. خواندنی/نوشتنی بایت.

**بازگشت:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

مقدار یا تنظیم مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 تا 100). در صورت true بودن مقدار ویژگی RightAngleAxes نادیده گرفته می‌شود. خواندنی/نوشتنی بایت.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

مشخص می‌کند که آیا محورهای نمودار با زاویه راست هستند یا به صورت پرسپکتیو رسم شده‌اند. به عبارت دیگر تعیین می‌کند آیا زوایای محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

مشخص می‌کند که آیا محورهای نمودار با زاویه راست هستند یا به صورت پرسپکتیو رسم شده‌اند. به عبارت دیگر تعیین می‌کند آیا زوایای محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. خواندنی/نوشتنی boolean.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

مقدار یا تنظیم عمق یک نمودار سه‌بعدی به عنوان درصدی از عرض نمودار (بین 20 تا 2000 درصد). خواندنی/نوشتنی int.

**بازگشت:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

مقدار یا تنظیم عمق یک نمودار سه‌بعدی به عنوان درصدی از عرض نمودار (بین 20 تا 2000 درصد). خواندنی/نوشتنی int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

مشخص می‌کند ارتفاع یک نمودار سه‌بعدی به عنوان درصدی از عرض نمودار (بین 5 تا 500 درصد). خواندنی/نوشتنی int.

**بازگشت:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

مشخص می‌کند ارتفاع یک نمودار سه‌بعدی به عنوان درصدی از عرض نمودار (بین 5 تا 500 درصد). خواندنی/نوشتنی int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |