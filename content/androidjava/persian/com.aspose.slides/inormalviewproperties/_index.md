---
title: INormalViewProperties
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایه‌های نمایش عادی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

نمایه‌های نمایش عادی را نشان می‌دهد. نمایش عادی شامل سه ناحیه محتوا است: خود اسلاید، یک ناحیه محتوا کناری، و یک ناحیه محتوا پایین.

## متدها

| متد | توضیح |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | مشخص می‌کند که آیا برنامه باید آیکون‌ها را در صورتی که محتویات طرح کلی را در هر یک از نواحی محتوا در حالت نمایش عادی نمایش دهد، نشان دهد یا خیر. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | مشخص می‌کند که آیا برنامه باید آیکون‌ها را در صورتی که محتویات طرح کلی را در هر یک از نواحی محتوا در حالت نمایش عادی نمایش دهد، نشان دهد یا خیر. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن ناحیه کناری به حالت کمینه بچسبد. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن ناحیه کناری به حالت کمینه بچسبد. |
| [getVerticalBarState()](#getVerticalBarState--) | حالت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | حالت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. |
| [getHorizontalBarState()](#getHorizontalBarState--) | حالت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | حالت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. |
| [getPreferSingleView()](#getPreferSingleView--) | مشخص می‌کند که آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک-پنجره‌ای تمام‌صفحه را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | مشخص می‌کند که آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک-پنجره‌ای تمام‌صفحه را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. |
| [getRestoredLeft()](#getRestoredLeft--) | این عنصر اندازه‌گیری ناحیه محتوا کناری نمایش عادی را زمانی که ناحیه در اندازه بازگردانده متغیر (نه کمینه نه بیشینه) باشد، مشخص می‌کند. |
| [getRestoredTop()](#getRestoredTop--) | این عنصر اندازه‌گیری ناحیه بالایی اسلاید نمایش عادی را زمانی که ناحیه در اندازه بازگردانده متغیر (نه کمینه نه بیشینه) باشد، مشخص می‌کند. |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

مشخص می‌کند که آیا برنامه باید آیکون‌ها را در صورتی که محتویات طرح کلی را در هر یک از نواحی محتوا در حالت نمایش عادی نمایش دهد، نشان دهد یا خیر. قابل خواندن/نوشتن Boolean.

**بازمی‌گردد:**  
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

مشخص می‌کند که آیا برنامه باید آیکون‌ها را در صورتی که محتویات طرح کلی را در هر یک از نواحی محتوا در حالت نمایش عادی نمایش دهد، نشان دهد یا خیر. قابل خواندن/نوشتن Boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن ناحیه کناری به حالت کمینه بچسبد. قابل خواندن/نوشتن Boolean.

**بازمی‌گردد:**  
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

مشخص می‌کند که آیا تقسیم‌کننده عمودی باید هنگام کوچک بودن ناحیه کناری به حالت کمینه بچسبد. قابل خواندن/نوشتن Boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

حالت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوا کناری جدا می‌کند.

**بازمی‌گردد:**  
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

حالت نمایش نوار تقسیم‌کننده عمودی را تعیین می‌کند. نوار تقسیم‌کننده عمودی اسلاید را از ناحیه محتوا کناری جدا می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

حالت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوا زیر اسلاید جدا می‌کند.

**بازمی‌گردد:**  
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

حالت نمایش نوار تقسیم‌کننده افقی را تعیین می‌کند. نوار تقسیم‌کننده افقی اسلاید را از ناحیه محتوا زیر اسلاید جدا می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

مشخص می‌کند که آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک-پنجره‌ای تمام‌صفحه را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از نواحی محتوا را در تمام پنجره نمایش دهد. قابل خواندن/نوشتن Boolean.

**بازمی‌گردد:**  
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

مشخص می‌کند که آیا کاربر ترجیح می‌دهد یک ناحیه محتوا تک-پنجره‌ای تمام‌صفحه را به جای نمایش عادی استاندارد با سه ناحیه محتوا ببیند. اگر فعال باشد، برنامه ممکن است یکی از نواحی محتوا را در تمام پنجره نمایش دهد. قابل خواندن/نوشتن Boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

این عنصر اندازه‌گیری ناحیه محتوا کناری نمایش عادی را زمانی که ناحیه در اندازه بازگردانده متغیر (نه کمینه نه بیشینه) باشد، مشخص می‌کند. فقط خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازمی‌گردد:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

این عنصر اندازه‌گیری ناحیه بالایی اسلاید نمایش عادی را زمانی که ناحیه در اندازه بازگردانده متغیر (نه کمینه نه بیشینه) باشد، مشخص می‌کند. فقط خواندنی [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**بازمی‌گردد:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)