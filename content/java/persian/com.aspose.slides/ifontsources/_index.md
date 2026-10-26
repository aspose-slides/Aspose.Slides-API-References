---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /fa/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

منابع فایل و حافظه برای فونت‌های خارجی را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | پوشه‌هایی که حاوی فایل‌های فونت هستند. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | پوشه‌هایی که حاوی فایل‌های فونت هستند. |
| [getMemoryFonts()](#getMemoryFonts--) | مجموعه‌ای از فونت‌ها که به صورت آرایه‌های بایت نمایانده شده‌اند. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | مجموعه‌ای از فونت‌ها که به صورت آرایه‌های بایت نمایانده شده‌اند. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

پوشه‌هایی که حاوی فایل‌های فونت هستند. تمام فایل‌های فونت موجود در این پوشه‌ها در مجموعه گنجانده می‌شوند. پوشه‌هایی که به صورت بازگشتی جستجو می‌شوند.

**بازگشت:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

پوشه‌هایی که حاوی فایل‌های فونت هستند. تمام فایل‌های فونت موجود در این پوشه‌ها در مجموعه گنجانده می‌شوند. پوشه‌هایی که به صورت بازگشتی جستجو می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

مجموعه‌ای از فونت‌ها که به صورت آرایه‌های بایت نمایانده شده‌اند.

**بازگشت:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

مجموعه‌ای از فونت‌ها که به صورت آرایه‌های بایت نمایانده شده‌اند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[][] |  |